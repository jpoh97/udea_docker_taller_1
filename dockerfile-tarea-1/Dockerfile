FROM node:6.14-alpine
EXPOSE 3000
RUN apk update && apk add --no-cache tini
WORKDIR /usr/src/app
COPY . .
RUN npm install && npm cache clean --force
ENTRYPOINT ["/sbin/tini", "--", "node", "./bin/www" ]