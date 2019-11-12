# Laravel (nginx + mysql + phpfpm)
## Precondition
- Docker (https://www.docker.com/)  
- Docker Compose (https://docs.docker.com/compose/)  

## Set up
  > `git clone https://github.com/sho-zy/laravelSample.git`  
  > `cd laravelSample`  
  > `cp .env.example .env`  
  > `docker-compose up -d`  
  > `docker-compose ps`  
  > `docker exec -it laravelsample_phpfpm_1 /bin/sh`  (enter the container)  
  > `composer install`  
  > `php artisan key:generate`  
  > `exit`    (exit the container)  
  > `docker-compose restart`

## URL
- Laravel Home  
  http://localhost/
