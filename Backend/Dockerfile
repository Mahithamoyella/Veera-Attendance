FROM node:18

WORKDIR /app

COPY package.json package-lock.json ./

RUN npm install

COPY server.js ./

EXPOSE 3076

CMD ["node", "server.js"]

