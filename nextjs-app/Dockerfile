FROM node:14-alpine
WORKDIR /app
COPY package*.json ./
RUN npm install
COPY . .
RUN npm run build
RUN npm audit fix
EXPOSE 3000
CMD ["npm", "start"]

