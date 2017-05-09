# Magento2 docker compose

Install full magento2 environment including magento2 pre-installed with sample data using only  **one** command line:
```sh
sudo docker-compose up
```

### Executing  docker-compose up will:
 1- create 3 docker containers : nginx , php-fpm (xdebug included) and mariadb.

 2- fetch magento2 from official repo.

 3- set files owner + permissions.

 4- install magento2.

 5- install sample-data.


