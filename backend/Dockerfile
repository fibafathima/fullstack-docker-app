# Backend Dockerfile
FROM node:14-alpine

# Set working directory
WORKDIR /app

# Copy package.json first
COPY package.json .

# Install dependencies
RUN npm install

# Copy app files
COPY . .

# Expose backend port
EXPOSE 5000

# Start server
CMD ["npm", "start"]
