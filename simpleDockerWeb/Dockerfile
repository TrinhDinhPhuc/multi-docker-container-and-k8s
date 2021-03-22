# specify a base image
FROM node:12-alpine

# Insatll some dependencies
WORKDIR /usr/app

COPY ./package.json ./
RUN npm install
COPY ./ ./


# Default command
CMD ["npm", "start"]

