Tutorial - https://www.youtube.com/watch?v=8ZPsZBcue50

## Docker

```
docker run --name spring-boot-and-angular -e MYSQL_ROOT_PASSWORD=letmein -d -p3306:3306 mysql:5.7
docker exec -it spring-boot-and-angular bash
mysql -u root -pletmein
create database serverdb
```