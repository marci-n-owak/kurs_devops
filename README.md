# Pliki z warsztatów (Docker)

Wszystkie komendy użyte podczas warsztatów

```sh
docker run ubuntu
docker run -dt --name my_ubuntu ubuntu 
docker exec -it my_ubuntu /bin/bash

apt update
apt install iputils-ping
ping localhost  
exit

docker build -t my_httpd . 
docker run -dt --name my_httpd -p 80:80 my_httpd

docker-compose up -d
docker-compose logs
```
