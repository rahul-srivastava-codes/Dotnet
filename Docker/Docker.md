# Learn to write docker file 
Step 1: Choose a base image->```FROM node:22-alpine```<br>
Step 2: Choose a working directory->```WORKDIR /app```<br>
Step 3: Copy package files->```COPY package*.json ./```<br>
Step 4: Install dependencies->```RUN npm install``` <br>
Step 5: Copy the application code->```COPY . .```<br>
Step 6: Document the port->```EXPOSE 5000```<br>
Step 7: Start the application->```CMD ["node", "index.js"]```<br>

# Build Command
```docker build -t node-project .```

# Commands
```docker build```<br>
```docker run```<br>
```docker ps```<br>
```docker logs```<br>
```docker exec```<br>
```docker stop```<br>
```docker rm```<br>
```docker rmi```<br>

# Volumes
```docker run -v mysql-data:/var/lib/mysql mysql```<br>
```docker volume ls```<br>
```docker volume inspect```<br>
```docker volume rm```<br>

# Network
```docker network create my-network```<br>
