# Run ubuntu18 in a container
#
# docker run -ti --name ubuntu tinobtp/ubuntu
#
FROM ubuntu:18.04
LABEL maintainer "Bao Pham<tinobtp@gmail.com>"

RUN apt-get update && \
    apt-get install -y software-properties-common --no-install-recommends && \
	apt-get update && \
	apt-get install -y git vim net-tools iftop
