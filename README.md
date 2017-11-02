# wordpress-nginx-php-fpm-mysql

# Prequites
1) Ubuntu Linux
2) docker-engine
3) docker-compose
  
1) git clone https://github.com/ljubon/wordpress-nginx-php-fpm-mysql.git 
2) docker stack deploy -c docker-compose.yml wp
3) [VERIFICATION] docker service ps wp_nginx wp_mysql wp_wordpress OR docker service ls

# Images

Ubuntu image - ubuntu/trusty64 \
Nginx - nginx:latest \
MariaDB - mariadb \
WordPress - wordpress:4.7.1-php7.0-fpm 

To start WordPress setup, open browser and open: http://[host IP]
