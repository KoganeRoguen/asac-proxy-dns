FROM nginx:latest
COPY 404.html /usr/share/nginx/html
COPY default.conf /etc/nginx/conf.d
COPY nginx.conf /etc/nginx

#site alisson.asa.br
RUN mkdir -p /usr/share/nginx/alisson
COPY index.html /usr/share/nginx/alisson