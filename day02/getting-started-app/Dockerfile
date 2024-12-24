FROM node:18-alpine

# Working directory in the continer
WORKDIR /app 

# Copy the files from the current directory to work directory in the container
COPY . .

# Install the dependencies
RUN yarn install --production

# Command is executed when the application is run
CMD ["node", "src/index.js"]

# Expose the application on a port
EXPOSE 3000