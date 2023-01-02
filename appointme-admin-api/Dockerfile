FROM node:17.9.0-slim

LABEL maintainer="mike babs"

RUN useradd adminapi

WORKDIR /app

COPY . .

RUN npm install

EXPOSE 5000

USER adminapi

ENV MONGO_URL=""

CMD ["npm", "start"]
