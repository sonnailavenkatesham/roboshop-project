FROM node:14
WORKDIR /app
COPY package.json /app
COPY server.js /app
RUN npm install
CMD [ "node", "server.js" ]