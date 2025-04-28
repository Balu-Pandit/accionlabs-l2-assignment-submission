# minimal and secure base image
FROM nginx:1.19-alpine

# Set labels
LABEL maintainer="your-email@example.com" \
      description="Secure Nginx 1.19 Container" \
      version="1.0"

# Expose port 80 
EXPOSE 80

USER nginx

# Start nginx as foreground  
CMD ["nginx", "-g", "daemon off;"]
