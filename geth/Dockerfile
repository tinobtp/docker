# Run geth in a container
#
# docker run -ti --name geth tinobtp/geth:0.01
#
FROM tinobtp/ubuntu:18.04.a
LABEL maintainer "Bao Pham<tinobtp@gmail.com>"

RUN apt-get update && \
    add-apt-repository -y ppa:ethereum/ethereum && \
	apt-get update && \
	apt-get install -y ethereum && \
	mkdir -p /root/.ssh && \
    rm -rf /var/lib/apt/lists/*
