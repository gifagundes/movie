FROM node:14-slim
WORKDIR /app
COPY ./package*.json .
RUN npm install
COPY . .
EXPOSE 8181
CMD [ "node", "server.js" ]