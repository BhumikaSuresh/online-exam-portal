FROM node:14

WORKDIR /app/user_frontend

COPY . .

RUN npm install --legacy-peer-deps

EXPOSE 3200

CMD ["npm", "start"]


