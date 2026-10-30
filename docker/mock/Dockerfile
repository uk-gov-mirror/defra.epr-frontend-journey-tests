FROM node:lts-alpine@sha256:c6ad9e9c1d80f6eb607c26b4b0a132ff7a2344fad1c78ea3baa2a7d4c8de6d94
WORKDIR /app
RUN npm init -y && npm install express
COPY ./docker/mock/waste.organisations.js .
EXPOSE 3020
CMD ["node", "waste.organisations.js"]
