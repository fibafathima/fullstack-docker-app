# Frontend Dockerfile
FROM node:14-alpine

# Set working directory
WORKDIR /app

# Copy package files
COPY package.json .

# Install dependencies
RUN npm install

# Copy rest of the project
COPY . .

# Expose frontend port
EXPOSE 3000

# Start React dev server
CMD ["npm", "start"]
