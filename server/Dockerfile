# Select a base image
FROM node:20-alpine3.17

#Create a directory and go to the directory
WORKDIR /app

#Copy the package.json file to my current directory to install the necessary dependencies
COPY package.json .

# Install the dependecy
RUN npm install

# Copy other files to my current directory
COPY . .

# Open the port for the epxress server
EXPOSE 5000

#Run express rum in the foreground
CMD ["npm", "start"]