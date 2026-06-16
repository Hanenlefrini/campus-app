FROM nginxinc/nginx-unprivileged:1.27-alpine

WORKDIR /usr/share/nginx/html

COPY index.html .
COPY styles.css .
COPY app.js .

COPY nginx.conf /etc/nginx/conf.d/default.conf