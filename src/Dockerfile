FROM node:lts-alpine3.18

WORKDIR /app
COPY . . 
RUN yarn install --production
CMD ["node", "/app/index.js"]
