FROM node:20-alpine as FE
WORKDIR /app/FE
COPY ./package*.json ./
RUN npm install
COPY . .
EXPOSE 3000
CMD ["npm", "run", "dev"]

