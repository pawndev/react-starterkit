FROM node:8

LABEL maintainer="Christophe Coquelet <christophe.coquelet@link-value.fr>"

RUN mkdir -p /usr/src/app

WORKDIR /usr/src

ADD src/package.json /usr/src/package.json

RUN npm install -g webpack webpack-dev-server grunt-cli gulp-cli

RUN npm install --silent

ENV PATH /usr/src/node_modules/.bin:$PATH

WORKDIR /usr/src/app
