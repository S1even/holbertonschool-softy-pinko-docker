# Use Nginx as a base image
FROM nginx:latest

# Copy front-end files to Nginx web directory
COPY ./softy-pinko-front-end /var/www/html/softy-pinko-front-end

# Copy Nginx configuration file
COPY ./softy-pinko-front-end.conf /etc/nginx/conf.d/default.conf
