FROM nginx:latest
COPY /ssl/* /etc/nginx/ssl/
COPY ./default.conf /etc/nginx/conf.d/default.conf
CMD ["nginx", "-g", "daemon off;"]
