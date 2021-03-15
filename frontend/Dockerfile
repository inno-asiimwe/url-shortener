FROM node:15.11.0-alpine

WORKDIR /app

COPY package.json package-lock.json ./

RUN npm install -g create-react-app && npm install

CMD ["npm", "start"]