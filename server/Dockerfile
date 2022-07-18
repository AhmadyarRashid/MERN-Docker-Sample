# DockerFile for Backend app

# Build React Client
From node:18-alpine

# Working directory app
RUN mkdir -p /usr/src/app
WORKDIR /usr/src/app
COPY package*.json ./

# Installing dependencies
RUN npm install --silent

# Copy local file into app app folder
COPY . .

EXPOSE 5000
CMD ["npm", "start"]