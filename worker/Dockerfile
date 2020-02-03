FROM node:alpine
WORKDIR '/app'
COPY ./package.json .
RUN yarn install
COPY . .
RUN ["yarn","start"]