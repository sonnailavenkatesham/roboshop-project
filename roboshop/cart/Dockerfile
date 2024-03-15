FROM node:14
WORKDIR /app
COPY package.json /app
COPY server.js /app
RUN npm install 
ENV REDIS_HOST=redis
ENV CATALOGUE_HOST=catalogue
ENV CATALOGUE_PORT=8080
CMD ["node", "server.js"]