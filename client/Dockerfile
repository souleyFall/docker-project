FROM node:alpine

WORKDIR /app

COPY package.json ./
RUN npm install

COPY ./ ./

ENV BROWSER=none
ENV WDS_SOCKET_PORT=0

CMD ["npm", "start"]
