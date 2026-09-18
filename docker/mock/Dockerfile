FROM node:lts-alpine@sha256:ebfe2f90462722a7a4de65e91990e97fe0d401c70e0e762c5b53302f905ec1c1
WORKDIR /app
RUN npm init -y && npm install express
COPY ./docker/mock/waste.organisations.js .
EXPOSE 3020
CMD ["node", "waste.organisations.js"]
