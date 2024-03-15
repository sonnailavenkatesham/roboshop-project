FROM node:14
EXPOSE 8080
RUN useradd roboshop
WORKDIR /app
USER roboshop
COPY package.json /app/
COPY server.js /app/
RUN npm install
CMD [ "node", "server.js" ]