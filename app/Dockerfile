FROM node:18.1-alpine

WORKDIR /app

RUN apk update && \
    npm install -g npm && \
    npm install -g vue-cli

EXPOSE 8080


# image-name: docker-vue-client

# 起動方法
# 1. docker-compose up -d
# 2. docker-compose exec client sh
# 3. npm run serve 
