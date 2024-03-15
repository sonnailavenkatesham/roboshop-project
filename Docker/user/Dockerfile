FROM node:14
EXPOSE 8080
WORKDIR /app
COPY package.json /app/
COPY server.js /app/
RUN npm install
CMD [ "node", "server.js" ]