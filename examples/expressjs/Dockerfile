FROM particle4dev/node:node-14.6.0-dumb-1.2.2
MAINTAINER Hoang Nam "particle4dev@gmail.com"
LABEL description="This is demo for particle4dev/node image"

# Set a working directory
WORKDIR /usr/src/app

COPY package-lock.json package.json index.js /usr/src/app/

# Install Node.js dependencies
RUN yarn install

EXPOSE 3000
CMD [ "npm", "start"]
