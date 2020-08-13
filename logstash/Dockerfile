FROM logstash:7.8.1

MAINTAINER hicjcn hicjcn@gmail

WORKDIR /usr/share/logstash/config/

RUN rm logstash.conf logstash-sample.conf logstash.yml

ADD ./logstash.conf /usr/share/logstash/pipeline/

CMD ["logstash"]

