###install docker compose ######

sudo curl -L https://github.com/docker/compose/releases/download/1.29.2/docker-compose-`uname -s`-`uname -m` -o /usr/local/bin/docker-compose
sudo chmod +x /usr/local/bin/docker-compose
docker-compose --version

###### create docker compose file and execute ########### 


docker-compose up

http://ip:8080

docker-compose down
