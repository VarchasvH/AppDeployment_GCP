FROM --platform=arm64 node:14

WORKDIR /usr/app

COPY package.json .

RUN npm install

COPY . .

EXPOSE 80

CMD ["node", "app.js"]