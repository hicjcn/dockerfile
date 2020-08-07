FROM nginx:1.19.1

MAINTAINER hicjcn hicjcn@gmail

WORKDIR /usr/share/nginx/html/

COPY ./dist/ /usr/share/nginx/html/

ADD ./nginx/default.conf /etc/nginx/conf.d/

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]

