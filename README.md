# docker-laravel-app
Dockerfile to build laravel app and docker compose file to define, create and manage services. 

### Dockerfile
- Built on ubuntu image.
- Installs apache2 and other dependencies.
- Copies source file for laravel app onto image.
- Installs laravel.
- Sets up apache2.
- Starts apache2.

### docker-compose.yml
- Laravel app service.
- MySQL db service for laravel app.
- Volumes for logs and persistent data.
- Network for services.

### laravel-realworld-example-app
- Source files for laravel app.

### laravel.conf
- Apache2 configurations for laravel app.

### .env.example
- Example env file.

### php.ini
- Php configurations.

### web.php
- Enable laravel landing page.

### Instructions
- specify db user password in ./docker-compose.yml
- Also DB_PASSWORD in .env.example
- run docker compose up -d #to create containers
