FROM node:8-alpine

RUN apk add --update git
RUN git clone https://github.com/YerayMM/blockchain-explorer.git

WORKDIR /blockchain-explorer
RUN npm install
CMD npm start

EXPOSE 8080