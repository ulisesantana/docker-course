FROM node:11-alpine

RUN npm install express sync-request

COPY src/app.js /app.js

CMD exec node app.js

EXPOSE 3000
