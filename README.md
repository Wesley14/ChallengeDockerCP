# ChallengeDockerCP
Después de clonar el proyecto correr los siguientes comandos:

1.-$ docker-compose build # trae y configura las imagenes
2.-$ docker-compose up -d # enciende los containers y la red
3.-$ docker-compose exec php composer install --ignore-platform-reqs
4.-$ docker-compose exec php php artisan key:generate
5.-$ docker-compose exec php php artisan config:clear
6.-$ docker-compose exec php php artisan cache:clear 
7.-$ docker-compose exec php php artisan view:clear 
8.-$ docker-compose exec php php artisan config:cache 
9.-$ docker-compose exec php php artisan migrate --seed

Una vez ejecutado los comandos nos dirijimos al navegador y ponemos el siguiente enlace: http://localhost:8888/
