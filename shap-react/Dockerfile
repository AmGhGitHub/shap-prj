FROM node:15.13-alpine

WORKDIR /react

ENV PATH /app/node_modules/.bin:$PATH


COPY package.json package-lock.json /react/
RUN npm install --silent && npm install react-scripts@3.4.1 -g --silent

COPY . /react/

RUN npm run build


