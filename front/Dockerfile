FROM node:9

LABEL maintainer="Christophe Coquelet <christophe.coquelet@link-value.fr>"

RUN mkdir /usr/src/app

WORKDIR /usr/src/app

ENV PATH /usr/src/app/node_modules/.bin:$PATH

ADD src/package.json /usr/src/app/package.json

RUN npm install --silent

EXPOSE 3000
