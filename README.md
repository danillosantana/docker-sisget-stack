⚙️ Comandos para implantar

1 Iniciar o Swarm (uma vez apenas):

docker swarm init


2 Implantar a stack:

docker stack deploy -c docker-compose.yml sisget


3 Ver status:

docker stack services sisget
docker service ps sisget-<nome-do-serviço>

4 Ver logs:

docker service logs -f <nome-do-serviço>



'docker build -t dsantana87/sis-gateway:latest .'

docker push dsantana87/sis-gateway:latest 