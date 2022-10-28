from node:14.17.5
workdir /app
copy package*.json ./
run npm install
copy . .
expose 8080
cmd ["node","server.js"]