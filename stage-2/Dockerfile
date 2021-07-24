FROM stage-1
COPY package*.json ./
RUN yarn install
COPY . .
CMD ["npm","run","start"]