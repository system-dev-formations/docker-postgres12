# Docker-postgresql12
Latest version of postgresql coming with timescaledb and pgloader
# Build 
```shell script
  git clone https://github.com/system-dev-formations/docker-postgres12.git
  cd docker-postgres12
  docker build -t pg122 . 
  docker run -d --name db -p 25432:5432 -e POSTGRES_PASSWORD=password  --rm -v /mnt:/var/lib/postgresql/data pg122 
```
# Run 
```shell script
  docker exec -it db /bin/bash
  
```