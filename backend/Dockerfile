FROM node:18

# Copy package.json and package-lock.json to the container
COPY package*.json ./

# Install application dependencies
RUN npm install

# Copy your backend code to the container
COPY . .

# Expose the port your Node.js application will listen on
EXPOSE 3000

# Command to start your Node.js application
CMD ["node", "index.js"]