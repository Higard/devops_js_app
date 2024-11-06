# Use official Node.js image as a base
FROM node:16

# Set the working directory inside the container
WORKDIR /app

# Copy package.json and install dependencies
COPY package.json /app/package.json
RUN npm install

# Copy the rest of the application files into the container
COPY . /app

# Expose the port the app runs on
EXPOSE 3000

# Set the command to run the app
CMD ["node", "index.js"]
