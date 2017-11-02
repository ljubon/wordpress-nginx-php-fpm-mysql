# wordpress-nginx-php-fpm-mysql

# Prequites
  - Ubuntu Linux
  - docker-engine
  - docker-compose
  
1) git clone https://github.com/ljubon/wordpress-nginx-php-fpm-mysql.git 
2) docker stack deploy -c docker-compose.yml wordpress-nginx-php-fpm wp

# Images

Ubuntu image - ubuntu/trusty64
Nginx - nginx:latest
MariaDB - mariadb
WordPress - wordpress:4.7.1-php7.0-fpm

To start WordPress setup, open browser and open: http://[host IP]
