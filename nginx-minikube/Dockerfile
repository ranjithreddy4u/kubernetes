# Use the official Nginx image as a base
FROM nginx:alpine

# Maintainer label
LABEL maintainer="Ranjith Reddy"

# Set environment variable
ENV Home=/home

# Set working directory
WORKDIR $Home
# Copy the current directory's index.html to the Nginx HTML directory
COPY ./index.html /usr/share/nginx/html/index.html

# Expose port 80 to the outside world
EXPOSE 80
