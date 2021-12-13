# Paypro Docker for Magento

base image: [bitnami - magento](https://hub.docker.com/r/bitnami/magento/)

## Requirements

- ports `80`, `3306` are available
- [docker-compose](https://docs.docker.com/compose/install/)

## Start docker

    docker-compose up -d

After it is installed open [magento - http://localhost](http://localhost:80)

- Admin page: [http://localhost/admin](http://localhost:80/admin)
- Admin username: `paypro`
- Admin password: `adminpaypro1`
- Admin email: `admin@paypro.nl`

- Database name: `paypro_magento_db`
- Database user: `paypro_magento_user`
- Database password: `paypro`