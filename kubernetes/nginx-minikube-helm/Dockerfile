# Use the official Nginx image as a base
FROM nginx:alpine

# Maintainer label
LABEL maintainer="Ranjith Reddy"

# Copy the current directory's index.html to the Nginx HTML directory
COPY ./index.html /usr/share/nginx/html/index.html

# Set environment variable
ENV HOME=/home

# Set working directory
WORKDIR $HOME

# Expose port 80 to the outside world
EXPOSE 80
