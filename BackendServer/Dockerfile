FROM node:14.21.3-bullseye-slim

WORKDIR /home/node/dvba

COPY package*.json ./
RUN npm install

COPY . .

EXPOSE 3000

CMD ["npm", "start"]