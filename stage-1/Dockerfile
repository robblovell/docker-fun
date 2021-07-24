FROM node:14.0.0-alpine3.10
COPY package*.json ./
RUN yarn install
COPY . .
CMD ["npm","run","start"]