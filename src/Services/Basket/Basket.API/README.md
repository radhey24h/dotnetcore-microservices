Microsoft.Extensions.Caching.StackExchangeRedis

Newtonsoft.json

Swashbuckle.AspNetCore


docker run -d -p 6379:6379 --name aspnetrun-redis redis

docker exec -it aspnetrun-redis /bin/bash
redis-cli
ping 


portainer/portainer

docker pull portainer/portainer-ce

Portainer is a lightweight management UI which allows you to easily manage your Docker host or Swarm cluster.
Portainer is meant to be as simple to deploy as it is to use. It consists of a single container that can run on any Docker engine (Docker for Linux and Docker for Windows are supported).