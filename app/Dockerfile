# Applicational container

# Use a slim version of the node image
FROM node:slim

# Set the workdir
WORKDIR /usr/src/app

# Copy the pacakge files
COPY package*.json ./

# Install the dependencies and fix any vulnerable package
RUN npm install
RUN npm audit fix

# Copy the source code
COPY . ./

# Environment variables default values
ENV PORT 3000

# Startup commands
CMD ["node", "index.js"]

# Exposr the port to the outside
EXPOSE 3000