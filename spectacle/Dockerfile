FROM node:8-alpine
MAINTAINER Jean Wallet <tokeneconomy@eclipso.eu>

USER 0
WORKDIR /opt

RUN apk add --no-cache \
  nodejs nodejs-npm g++ \
  python python-dev

RUN npm install --unsafe-perm -g spectacle-docs
