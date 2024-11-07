FROM node:14

WORKDIR /app/backend

COPY . .

RUN npm install

RUN npm install nodemon

EXPOSE 5000

CMD ["npm", "start"]