FROM logstash:7.8.1

MAINTAINER hicjcn hicjcn@gmail

WORKDIR /usr/share/logstash/config/

ADD ./logstash.conf /usr/share/logstash/config/

CMD ["logstash", "-f", "logstash.conf"]

