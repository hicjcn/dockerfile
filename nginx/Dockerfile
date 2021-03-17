FROM nginx:1.19.1

MAINTAINER hicjcn hicjcn@gmail.com

WORKDIR /usr/share/nginx/html/

ADD ./nginx.conf /etc/nginx/

EXPOSE 443

CMD ["nginx", "-g", "daemon off;"]

