FROM node:16

COPY . .

RUN npm install
RUN npm install -g serve
RUN npm run build

CMD node index.js