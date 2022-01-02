# loki-docker-nginx-example

# Before launching
> docker plugin install grafana/loki-docker-driver:latest --alias loki --grant-all-permissions

# Launch
> docker-compose up -d

# Add some nginx logs
> curl localhost:8000
> 
> curl localhost:8000/not-exists

# See logs on grafana
[Local Grafana](http://localhost:3000)
