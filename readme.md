**запуск и билд сборки**
docker-compose up --build
или
docker-compose up --build -f docker-compose.yaml

**проверка сети**
(пример: 
проект назван docker-client-server
сервера -  server-service,  client-service,  database-service)

docker ps 
выдаст запущенный контейнер проекта базы + имя проекта, в примере 
0.0.0.0:5432->5432/tcp, :::5432->5432/tcp   docker-client-server_database-service_1

docker network ls
дает сеть docker-client-server_default в примере типа bridge
по названию проекта



