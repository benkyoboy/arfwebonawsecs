# Use a base image with the Nginx web server
FROM nginx:alpine

# Copy your local website files to the Nginx public directory in the container
COPY ./web /usr/share/nginx/html/

# Expose port 80 (for documentation purposes, doesn't publish the port)
EXPOSE 80

# Start Nginx when the container starts.
CMD ["nginx", "-g", "daemon off;"]
