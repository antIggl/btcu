FROM ubuntu:18.04

MAINTAINER Antonios Inglezakis inglezakis.a@unic.ac.cy

RUN apt-get update && \
	apt-get install -y build-essential libtool bsdmainutils autotools-dev autoconf pkg-config automake python3 \
			librocksdb-dev libjsoncpp-dev libssl-dev libgpm-dev libgmp-dev libevent-dev libboost-all-dev \
			libminiupnpc-dev libzmq3-dev software-properties-common\
			libqt5gui5 libqt5core5a libqt5dbus5 libqt5svg5-dev libqt5charts5-dev  qttools5-dev qttools5-dev-tools

RUN add-apt-repository ppa:pivx/pivx && apt-get update && apt-get install -y libdb4.8-dev libdb4.8++-dev

CMD /bin/bash
