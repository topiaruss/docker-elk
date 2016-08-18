FROM logstash:latest

# Add your logstash plugins setup here
# Example: RUN logstash-plugin install logstash-filter-json

 COPY config /etc/logstash/conf.d

 RUN logstash-plugin install logstash-input-beats
