FROM node:17.9.0-slim

LABEL maintainer="mike babs"

RUN useradd userapi

WORKDIR /app

COPY . .

RUN npm install

EXPOSE 5000

USER userapi

ENV MONGO_URL=""

ENV ADMIN_EMAIL=""

CMD ["npm", "start"]
