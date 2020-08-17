FROM fluent/fluentd:latest
RUN fluent-gem install fluent-plugin-elasticsearch  --no-ri --no-rdoc
RUN fluent-gem install fluent-plugin-grok-parser --no-rdoc --no-ri 
ADD fluent.conf /fluentd/etc



