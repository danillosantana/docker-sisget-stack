⚙️ Comandos para implantar

1️⃣ Iniciar o Swarm (uma vez apenas):

docker swarm init


2️⃣ Implantar a stack:

docker stack deploy -c docker-compose.yml sisget


3️⃣ Ver status:

docker stack services sisget
docker service ps sisget-<nome-do-serviço>