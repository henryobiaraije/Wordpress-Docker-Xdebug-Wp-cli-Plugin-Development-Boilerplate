## Wordpress plugin + Docker
### Description
This is my docker setup for wordpress plugin development. It is based on the [official wordpress docker image](https://hub.docker.com/_/wordpress/). It uses the [official mysql docker image](https://hub.docker.com/_/mysql/) as database. The database is stored in a docker volume. The wordpress files are stored in a docker volume as well. The wordpress files are mounted into the wordpress container. The database is mounted into the mysql container. 

### Usage
1. Clone this repository
2. Run `docker-compose -f docker-compose.yml up --build -d` to start the containers
