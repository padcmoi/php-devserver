# Use the official Node.js image from the Docker Hub
ARG PHP_VERSION=8.2
FROM php:${PHP_VERSION}-apache

# RUN apk add nano

# RUN npm install -g nodemon pnpm

# RUN echo "Node version: $(node -v)" >/.run.file

CMD ["apachectl", "-D", "FOREGROUND"]
