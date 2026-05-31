# ---- Pawan Rana Profile Card ----
# Base image: lightweight nginx web server
FROM nginx:alpine

# Set working directory
WORKDIR /usr/share/nginx/html

# Remove default nginx page
RUN rm -f index.html

# Copy profile HTML into container
COPY index.html .

# Expose port 80
EXPOSE 80

# Start nginx
CMD ["nginx", "-g", "daemon off;"]
