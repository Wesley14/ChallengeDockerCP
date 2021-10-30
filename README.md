# ChallengeDockerCP
Después de clonar el proyecto correr los siguientes comandos:

$ docker-compose build # trae y configura las imagenes
$ docker-compose up -d # enciende los containers y la red
$ docker-compose exec php composer install --ignore-platform-reqs
$ docker-compose exec php php artisan key:generate
$ docker-compose exec php php artisan config:clear
$ docker-compose exec php php artisan cache:clear 
$ docker-compose exec php php artisan view:clear 
$ docker-compose exec php php artisan config:cache 
$ docker-compose exec php php artisan migrate --seed

Una vez ejecutado los comandos nos dirijimos al navegador y ponemos el siguiente enlace: http://localhost:8888/
