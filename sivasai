# Use official Node.js image
FROM node:18-alpine

# Set working directory
WORKDIR /app

# Copy files
COPY server.js .

# Install dependencies (none needed in this example)
RUN npm install express

# Expose port
EXPOSE 3000

# Command to run the app
CMD ["node", "server.js"]
