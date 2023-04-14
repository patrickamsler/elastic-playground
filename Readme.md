# Elastic Playground

This is a playground for Elastic Stack. It is based on the Elasticsearch and Kibana Docker images.

## How to run Elastic
1. `cd elastic-playground/docker/elastic`
2. `docker-compose up -d`

Access Kibana: http://localhost:5601

username: `elastic`
 
password: `elastic`

###  Clean Up
`docker-compose down -v`

removes network, containers, and volumes.