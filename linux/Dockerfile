FROM ubuntu

RUN apt-get update
RUN apt-get -y install build-essential
RUN apt-get -y install git
RUN apt-get -y install inetutils-ping
RUN git clone https://github.com/Microsoft/ntttcp-for-linux
RUN cd ntttcp-for-linux/src && make && make install

EXPOSE 5000-5200
ENTRYPOINT ["ntttcp", "-r", "-t", "300", "-V"]

