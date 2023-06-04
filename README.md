A very simple app, that can be deployed using Docker Compose. All you need to do is to clone the repo and execute ```docker compose up -d``` to launch the app. 

The compose file will launch 2 containers based on php:8.0-apache and mariadb:10.7, then insert the data needed for the application. Once the containers are started and running, you can access the app on port 8080.
