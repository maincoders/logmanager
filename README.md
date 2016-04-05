## Log aggregation using Fluentd, Elasticsearch and Kibana

Inspired by http://docs.fluentd.org/articles/free-alternative-to-splunk-by-fluentd

## Running locally via docker

1. Install Docker
2. Clone this repo
2. `make run`
3. Visit `http://localhost:5601/` or docker-machine ip and port 5601
4. Connect the application to stream the log.


## TODO

Include AWS ECS example -- that does bootstrap Elasticsearch, Kibana, and Fluentd cluster. 