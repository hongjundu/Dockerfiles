# docker build . -t ubuntu-gcc:18.04

FROM ubuntu:18.04

RUN echo "">/etc/apt/sources.list && \
	echo "deb http://mirrors.aliyun.com/ubuntu/ bionic main restricted universe multiverse">>/etc/apt/sources.list && \
	echo "deb http://mirrors.aliyun.com/ubuntu/ bionic-security main restricted universe multiverse">>/etc/apt/sources.list && \
	echo "deb http://mirrors.aliyun.com/ubuntu/ bionic-updates main restricted universe multiverse">>/etc/apt/sources.list && \
	echo "deb http://mirrors.aliyun.com/ubuntu/ bionic-proposed main restricted universe multiverse">>/etc/apt/sources.list && \
	echo "deb http://mirrors.aliyun.com/ubuntu/ bionic-backports main restricted universe multiverse">>/etc/apt/sources.list && \
	echo "deb-src http://mirrors.aliyun.com/ubuntu/ bionic main restricted universe multiverse">>/etc/apt/sources.list && \
	echo "deb-src http://mirrors.aliyun.com/ubuntu/ bionic-security main restricted universe multiverse">>/etc/apt/sources.list && \
	echo "deb-src http://mirrors.aliyun.com/ubuntu/ bionic-updates main restricted universe multiverse">>/etc/apt/sources.list && \
	echo "deb-src http://mirrors.aliyun.com/ubuntu/ bionic-proposed main restricted universe multiverse">>/etc/apt/sources.list && \
	echo "deb-src http://mirrors.aliyun.com/ubuntu/ bionic-backports main restricted universe multiverse">>/etc/apt/sources.list && \
	apt-get update && \
	apt-get upgrade -y && \
	apt-get install build-essential -y

CMD ["/bin/sh"]
