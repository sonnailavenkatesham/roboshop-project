FROM node:14
EXPOSE 8080
RUN adduser roboshop
WORKDIR /app
COPY package.json /app
COPY server.js /app
RUN npm install
ENV MONGO=true
CMD [ "node", "server.js" ]