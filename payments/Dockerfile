FROM node:alpine

WORKDIR /app
COPY package.json .
RUN npm install --omit=dev --legacy-peer-deps
COPY . .

CMD ["npm", "start"],