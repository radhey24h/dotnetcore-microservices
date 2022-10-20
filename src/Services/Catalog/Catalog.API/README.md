docker ps
docker pull mongo
docker run -d -p 27017:27017 --name shopping-mongo mongo
docker logs -f shopping-mongo
docker exec -it shopping-mongo /bin/bash

The mongo shell is removed from MongoDB 6.0. The replacement is 
mongosh

docker exec -it shopping-mongo mongosh


docker ps -aq

 docker rm $(docker ps -aq)

docker images -q

 docker rmi $(docker images -q)

docker system prune

docker-compose -f .\docker-compose.yml -f .\docker-compose.override.yml up -d

docker-compose -f .\docker-compose.yml -f .\docker-compose.override.yml down