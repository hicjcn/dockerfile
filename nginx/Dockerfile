FROM nginx:1.19.1

MAINTAINER hicjcn hicjcn@gmail

WORKDIR /usr/share/nginx/html/

ADD ./nginx.conf /etc/nginx/

ADD ./default.conf /etc/nginx/conf.d/

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]

