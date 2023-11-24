FROM node:20.6-alpine3.17
WORKDIR /app
COPY . .
RUN yarn install
RUN yarn build
EXPOSE 3001
CMD [ "yarn", "start"]