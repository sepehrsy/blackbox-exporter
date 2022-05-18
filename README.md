# blackbox-exporter
#### Setup blackbox-exporter on Ubuntu Server

#### first of all we must prepare docker-compose.yml
```
cp docker-compose.yml /root/
```
#### then we must prepare blackbox.yml
```
cp blackbox.yml /blackbox-exporter/
```
#### after all
```
cd /root
docker-compose up -d
```
#### URL:
##### http://bbexporter_server_ip:9115/ 
