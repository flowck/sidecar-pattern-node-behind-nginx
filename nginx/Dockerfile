# This container uses a nginx image
FROM nginx
# Remove the default configuration file
RUN rm /etc/nginx/conf.d/default.conf
# Copy the new configuration file inside the container
COPY nginx.conf /etc/nginx/conf.d/default.conf

# Default values of nginx host and port env variables 
ENV NGINX_HOST app:3000
ENV NGINX_PORT 80