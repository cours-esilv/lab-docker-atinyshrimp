FROM nginx:latest

# Copy additional files or directories besides entrypoint.sh if needed
COPY entrypoint.sh /app/front/entrypoint.sh

# Copy your HTML page and other assets
COPY . /usr/share/nginx/html

ENV WS_BACK_URL http://localhost:8080

EXPOSE 80

ENTRYPOINT ["/app/front/entrypoint.sh"]