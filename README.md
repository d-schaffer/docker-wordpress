# docker-wordpress

This repo is a development environment for Wordpress / plugins / themes based on Docker

## Functionality:
Docker configuration: The Docker Compose files in this repository enable easy deployment and management of WordPress, MySQL and PHPMyAdmin containers.

Structured directory structure: The repository is structured in such a way that plugins and themes can be easily managed and developed.

## How To:
### Clone Repo
check php config file -> config/php.conf.ini
and set up .env.example or change it to .env
```
cp .env.example .env
```
### start your Docker Container 
```
 docker-compose up 
 #or without logs (-d = detach)
 docker-compose up -d
```
