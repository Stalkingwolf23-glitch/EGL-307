FROM node:alpine
WORKDIR /app

COPY package.json /app
RUN npm install

EXPOSE 3000

COPY package.json ./
CMD ["npm","run","start"]

