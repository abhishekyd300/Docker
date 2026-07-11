FROM node:18.16.0-alpine3.18
WORKDIR /index
COPY package*.json ./
RUN npm install
COPY . .
EXPOSE 3000
CMD ["node", "index.js"]