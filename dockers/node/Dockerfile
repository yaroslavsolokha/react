# https://hub.docker.com/_/node/

FROM node:alpine
RUN apk update && apk add nodejs
RUN npm install -g create-react-app
WORKDIR /app/projects