FROM logstash:7.8.1

MAINTAINER hicjcn hicjcn@gmail

WORKDIR /usr/share/logstash/config/

RUN rm /usr/share/logstash/config/logstash.conf /usr/share/logstash/config/logstash-sample.conf /usr/share/logstash/config/logstash.yml

ADD ./logstash.conf /usr/share/logstash/pipeline/

CMD ["logstash"]

