FROM node:14

WORKDIR /app/user_frontend

COPY . .

RUN npm install --legacy-peer-deps

EXPOSE 3000

CMD ["npm", "start"]


