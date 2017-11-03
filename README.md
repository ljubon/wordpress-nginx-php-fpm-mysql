# wordpress-nginx-php-fpm-mysql

# Prequites
1) docker-engine
2) docker-compose
  
1) git clone https://github.com/ljubon/wordpress-nginx-php-fpm-mysql.git 
2) ./docker-deploy.sh
3) [VERIFICATION] \
  - docker service ps wp_nginx wp_mysql wp_wordpress OR docker service ls
  - docker stack ls

# Images

Nginx - nginx:latest \
MariaDB - mariadb \
WordPress - wordpress:4.7.1-php7.0-fpm 

To start WordPress setup, open browser and open: http://[host IP]
