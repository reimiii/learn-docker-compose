run `docker compose create` where `docker-compose.yaml` is create


```bash
docker container ls -a # show all
docker container ls # show only running

docker compose start # to run container 
docker compose stop # to stop container 

# show only created with docker-compose
docker compose ps

docker compose down # for removing all container

docker compose ls # to show current proses config file

# for realtime monitoring event
docker events --filter 'container=name'
```
