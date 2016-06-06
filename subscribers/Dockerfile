FROM node:argon
RUN mkdir /client
WORKDIR /client

RUN git clone https://github.com/cxz/thor
RUN git checkout -b slanger
RUN npm install
ADD . /client
