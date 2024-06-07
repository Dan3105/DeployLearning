FROM nginx:1.15.12-alpine

# Copy the custom Nginx configuration
COPY ./default.conf /etc/nginx/conf.d/

# Expose the port
EXPOSE 80

# Start Nginx
CMD ["nginx", "-g", "daemon off;"]