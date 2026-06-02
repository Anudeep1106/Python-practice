# Base image
FROM nginx:latest

# Remove default nginx content
RUN rm -rf /usr/share/nginx/html/*

# Add your custom HTML
COPY index.html /usr/share/nginx/html/

# Expose port
EXPOSE 80

# Start nginx
CMD ["nginx", "-g", "daemon off;"]
