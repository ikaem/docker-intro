# Specify a base image 
FROM node:alpine
WORKDIR /usr/app

# Copy local files before npm install - package.json
COPY ./package.json ./

# Install some dependcies 
RUN npm install 

# Copy everything else that has changed 
COPY ./ ./

# Setup default command 
CMD ["npm", "start"]