FROM node:10.22.0-alpine3.11

RUN npm install -g serve

EXPOSE 5000

COPY build /site

WORKDIR /

ENTRYPOINT serve -s site
