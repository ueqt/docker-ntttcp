FROM ubuntu

RUN apt-get update
RUN apt-get -y install build-essential
RUN apt-get -y install git
RUN git clone https://github.com/Microsoft/ntttcp-for-linux
RUN cd ntttcp-for-linux/src && make && make install

ENTRYPOINT ["ntttcp", "-r", "-t", "300"]

