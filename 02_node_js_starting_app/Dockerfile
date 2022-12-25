FROM node:18.12.1

WORKDIR /app

COPY package.json /app/

RUN npm install 

COPY . /app

EXPOSE 3001

CMD ["node", "server.js"]