FROM logstash:7.8.1

MAINTAINER hicjcn hicjcn@gmail.com

WORKDIR /usr/share/logstash/config/

RUN rm logstash-sample.conf

ADD ./logstash.yml /usr/share/logstash/config/

ADD ./logstash.conf /usr/share/logstash/pipeline/

CMD ["logstash"]

