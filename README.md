The purpose of this repository is a local environment with some monitoring for meets.
    
# Services

## Nginx

Reverse proxying. Deals with ssl and http protocol level.
1. List new service in sites_enabled.
2. Generate a new ssl cert with the new subdomain.

## Elasticsearch
Collect logs and metrics from containers. Uses filebeat to collect logs via docker. As log as your logs are in json format the parsing is automatic. 

## Kibana
GUI for monitoring of elasticsearch data.