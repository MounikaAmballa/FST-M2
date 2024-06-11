FROM docker.io/node:18-alpine
WORKDIR /usr/app
COPY ./package.json ./
RUN npm install -g npm@10.8.1
RUN npm install
COPY . .
CMD ["npm", "run", "start"]