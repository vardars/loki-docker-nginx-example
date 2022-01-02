# loki-docker-nginx-example
[Blog Post](https://blog.ruanbekker.com/blog/2020/08/13/getting-started-on-logging-with-loki-using-docker/)

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
