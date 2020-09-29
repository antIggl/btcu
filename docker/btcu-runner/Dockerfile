#FROM antiggl/btcu-builder
FROM ubuntu:18.04

#WORKDIR /root/workspace/btcu
#COPY . /root/workspace/btcu
COPY ./btcu-bin/bin /usr/local/bin
COPY ./btcu-bin/share /usr/local/share

RUN apt-get update && apt-get install -y libboost-all-dev
#libqt5gui5 libqt5dbus5


