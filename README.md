## Docker with LAMP stack based on Alpine Linux

This docker contain a LAMP stack installed from scratch

## Installation
### Grab from docker hub
```
docker run -d -v /path/to/project:/var/www/localhost/htdocs/ -v /path/to/mysql/data:/var/lib/mysql -e MYSQL_ROOT_PASSWORD=password -p 80:80 -p 3306:3306 --name lamp rakarun93/nxtcld:v1
```



### Connect to MariaDB
To use this you need to install mysql/mariadb cli client
```
mysql -uroot -ppassword -h 127.0.0.1
```



https://hub.docker.com/r/rakarun93/nxtcld
