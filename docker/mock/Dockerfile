FROM node:lts-alpine@sha256:44fce696f38ba8c987c4db89954051000bbd05ffd8d8659ba15ed4a8602e937f
WORKDIR /app
RUN npm init -y && npm install express
COPY ./docker/mock/waste.organisations.js .
EXPOSE 3020
CMD ["node", "waste.organisations.js"]
