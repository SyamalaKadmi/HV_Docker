# Use an official Nginx base image
FROM nginx:latest

# Copy the `index.html` and `nginx.conf` files into the appropriate location in the container
COPY index.html /usr/share/nginx/html/index.html
COPY nginx.conf /etc/nginx/nginx.conf

# Listen to port 80
EXPOSE 80

# Ensure that the Nginx server is started when the container is run
CMD ["nginx", "-g", "daemon off;"]