Place the file `docker-compose.yaml `in directory and run

`docker compose -p MyWpProject up -d`

The following will images will be downloaded (If not already available) and configured.

1. Latest version of MariaDB
2. Latest source code of WordPress
3. Latest apache webserver

To stop all the containers for this project run the following command

`docker compose -p MyWpProject down`
`
