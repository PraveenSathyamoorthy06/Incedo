FROM node:18-alpine

WORKDIR /app/

COPY package*.json ./
RUN npm install
# COPY . /app

# EXPOSE 5001
CMD ["npm", "start"]
# CMD ["node_modules/.bin/nodemon", "./bin/www"]