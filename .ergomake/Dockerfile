FROM node:lts-hydrogen

WORKDIR /app

COPY ../package*.json ./
COPY docker-entrypoint.sh /docker-entrypoint.sh

COPY . .

EXPOSE 3000

CMD ["sh", "/docker-entrypoint.sh"]