# Usage: docker build . -t ubuntu-gcc:16.04

FROM ubuntu:16.04

RUN echo "">/etc/apt/sources.list && \
	echo "deb http://mirrors.163.com/ubuntu/ xenial main restricted universe multiverse">>/etc/apt/sources.list && \
	echo "deb http://mirrors.163.com/ubuntu/ xenial-security main restricted universe multiverse">>/etc/apt/sources.list && \
	echo "deb http://mirrors.163.com/ubuntu/ xenial-updates main restricted universe multiverse">>/etc/apt/sources.list && \
	echo "deb http://mirrors.163.com/ubuntu/ xenial-proposed main restricted universe multiverse">>/etc/apt/sources.list && \
	echo "deb http://mirrors.163.com/ubuntu/ xenial-backports main restricted universe multiverse">>/etc/apt/sources.list && \
	echo "deb-src http://mirrors.163.com/ubuntu/ xenial main restricted universe multiverse">>/etc/apt/sources.list && \
	echo "deb-src http://mirrors.163.com/ubuntu/ xenial-security main restricted universe multiverse">>/etc/apt/sources.list && \
	echo "deb-src http://mirrors.163.com/ubuntu/ xenial-updates main restricted universe multiverse">>/etc/apt/sources.list && \
	echo "deb-src http://mirrors.163.com/ubuntu/ xenial-proposed main restricted universe multiverse">>/etc/apt/sources.list && \
	echo "deb-src http://mirrors.163.com/ubuntu/ xenial-backports main restricted universe multiverse">>/etc/apt/sources.list && \ 
	apt-get update && \
	apt-get upgrade -y && \
	apt-get install build-essential -y

CMD ["/bin/sh"]