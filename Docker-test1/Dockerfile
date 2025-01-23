FROM ubuntu:18.04 as base

WORKDIR /install

RUN apt-get update && \
    apt-get install -y software-properties-common curl gnupg

RUN add-apt-repository ppa:kalon33/gamesgiroll -y


FROM ubuntu:18.04 as one