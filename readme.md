# Laravel (nginx + mysql + phpfpm)
## Precondition
- Docker (https://www.docker.com/)  
- Composer (https://getcomposer.org/)  

## Set up
  > `git clone https://github.com/sho-zy/laravelSample.git`  
  > `docker-compose up -d`  
  > `docker exec -it laravelsample_phpfpm_1 /bin/sh`  (enter the container)  
  > `composer install`  
  > `php artisan key:generate`  
  > `exit`    (exit the container)  
  > `docker-compose restart`

## URL
- laravel Home  
  http://localhost/
