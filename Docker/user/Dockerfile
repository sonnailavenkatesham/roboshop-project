FROM node:14
EXPOSE 8080
WORKDIR /app
COPY package.json /app
COPY server.js /app
RUN npm install
ENV MONGO=true
CMD [ "node", "server.js" ]