Pour monter les containers : 
à la racine du projet : 
docker compose up --build -d 

ensuite : 
docker exec -ti {container-php} symfony serve --allow-http
