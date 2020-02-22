FROM node:12.0

RUN mkdir -p /usr/mi-app

WORKDIR /usr/mi-app

COPY package.json .

RUN npm install

COPY . .

EXPOSE 4200

CMD ["npm", "start"]
