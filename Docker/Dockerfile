FROM ubuntu:18.04 AS base

RUN apt-get update && apt-get install -y software-properties-common git

RUN apt-key adv --keyserver hkp://keyserver.ubuntu.com:80 --recv-keys CE7709D068DB5E88
RUN add-apt-repository "deb https://repo.sovrin.org/sdk/deb bionic stable"
RUN apt-get update
RUN apt-get install -y libindy=1.16.0-bionic

RUN git clone https://github.com/esatus/didcreation.git
RUN chmod +x /didcreation/Linux_x64/DIDCreation