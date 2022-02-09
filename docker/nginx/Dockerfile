FROM nginx:1.21-alpine

ADD index.html /usr/share/nginx/html/index.html

COPY images/ /usr/share/nginx/html/images

CMD ["nginx", "-g", "daemon off;"]