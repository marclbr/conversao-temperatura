FROM  node:19.4.0
WORKDIR /app
copy package*.json ./
RUN npm install
copy . . 
EXPOSE 8080
cmd ["node", "server.js"]