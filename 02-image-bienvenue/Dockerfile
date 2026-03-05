#descripteur : un elt permanent

FROM nginx:1.29.5-alpine

COPY ./index.html /usr/share/nginx/html/index.html
COPY ./default.conf /etc/nginx/conf.d/default.conf

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]