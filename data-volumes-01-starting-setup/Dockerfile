FROM node:14

WORKDIR /app

COPY package.json .

RUN npm install

ENV PORT 80

COPY . .

EXPOSE 80



CMD [ "node", "server.js"] 