FROM node:18-alpine as BE
WORKDIR /app/BE
COPY ./package*.json ./
RUN npm install
COPY . .
EXPOSE 3000
CMD ["npm", "run", "dev"]