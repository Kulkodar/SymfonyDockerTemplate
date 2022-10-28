# Symfony Template
Just a small sample project based on symfony with preconfigured nginx and a database.

## Technologies
This project used following technologies:
- [symfony](https://symfony.com/)
- [docker](https://www.docker.com/)
- [nginx](https://nginx.org/en/)
- [php-fpm](https://php-fpm.org/)

## Setup
```shell
docker-compose up -d
docker exec -it server bash
composer update
```

## Starting the project
To start the symfony app:
```shell
docker-compose up -d
```

## Deploying
TODO

## Directory Structure
```
bin/          - Folder for symfony binaryies installed via composer
config/       - Contains various symfony configs
docker/       - Contains files used with docker
 db/          - Folder for the database used
 nginx/       - Contains the nginx configuration 
migrations/   - Folder for database migrations
public/       - The webroot of the project
src/          - Contains the backend code
templates/    - Contains twig templates that are used to render the frontend
tests/        - Contains phpunti tests
translations/ - The location of translation files
```