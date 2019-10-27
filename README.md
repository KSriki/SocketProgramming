# SocketProgramming
Repo using Docker for learning about Python Socket Programming

Tutorials used:
 - [Docker-Compose Server Client](https://www.freecodecamp.org/news/a-beginners-guide-to-docker-how-to-create-a-client-server-side-with-docker-compose-12c8cf0ae0aa/)
 - [Socket Programming](https://lipyeow.github.io/ics421s18/morea/sockets/experience-sockets.html)


```bash
docker run -it --name=n1 ubuntu
apt-get -y update
apt-get -y install iputils-ping
apt-get -y install iproute2
apt-get -y install dnsutils

# 'ip a' gives:
172.17.0.2/16

docker run -it --name=n2 ubuntu
apt-get -y update
apt-get -y install iputils-ping
apt-get -y install iproute2
apt-get -y install dnsutils

# 'ip a' gives:
172.17.0.3/16

```

apt-get -y install python3
apt-get -y install python3-pip
apt-get -y install vim
apt-get -y install sqlite3

# Create user
adduser sriki
su sriki
cd
mkdir test0
cd test0