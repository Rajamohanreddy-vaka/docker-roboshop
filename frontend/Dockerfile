FROM nginx:1.24

RUN rm /etc/nginx/nginx.conf /etc/nginx/conf.d/default.conf
RUN rm -rf /usr/share/nginx/html/* 
COPY index.html /usr/share/nginx/html
COPY nginx.conf /etc/nginx/nginx.conf