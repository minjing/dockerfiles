FROM isaserver2.global.tektronix.net/ubuntu
MAINTAINER xquan
RUN \
    echo oracle-java8-install shared/accepted-oracle-license-v1-1 select true | debconf-set-selections && \
    apt-get install -y software-properties-common && \
    add-apt-repository -y ppa:webupd8team/java && \ 
    apt-get update && \
    apt-get install -y oracle-java8-installer && \
    apt-get clean

