FROM ghcr.io/puppeteer/puppeteer:latest

WORKDIR /app

COPY package.json ./

RUN npm install

COPY . .

EXPOSE 5000

CMD ["npm", "start"]

