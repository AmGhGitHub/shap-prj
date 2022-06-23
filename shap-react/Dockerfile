FROM node:15.13-alpine

WORKDIR /app

ENV PATH /app/node_modules/.bin:$PATH


COPY package.json package-lock.json ./
RUN npm install --silent && npm install react-scripts@3.4.1 -g --silent

# add app
COPY . ./

# start app
CMD ["npm", "start"]