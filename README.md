# Docker

For ubuntu OS
    su root
    apt-get update
    apt-get install openjdk-8-jdk
    apt-get install docker.io
    systemctl status docker

For Linux OS
sudo yum update -y
sudo yum install docker -y
sudo systemctl start docker
sudo systemctl enable docker
sudo systemctl status docker
sudo docker pull tomcat
sudo docker images
docker pull mysql:5.7
docker images
docker image inspect mysql:5.7


docker build -t aqua:v1 .
docker run -it -d --name webcon1 -p 8081:80 aqua:v1
