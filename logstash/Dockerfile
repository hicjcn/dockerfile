FROM logstash:7.8.1

MAINTAINER hicjcn hicjcn@gmail

WORKDIR /usr/share/logstash/config/

RUN rm logstash-sample.conf && rm -rf /usr/share/logstash/pipeline/

ADD ./logstash.conf /usr/share/logstash/config/

CMD ["logstash"]

