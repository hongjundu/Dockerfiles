# Usage: docker build . -t go-gcc:latest

FROM golang:1.14

RUN apt-key adv --keyserver keyserver.ubuntu.com --recv-keys 40976EAF437D05B5 && \
	apt-get update && \
	apt-get upgrade -y && \
	apt-get install libcurl4-openssl-dev -y


CMD ["/bin/sh"]