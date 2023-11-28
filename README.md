# docker-main
# Atividade Sistemas Distribuidos

## Executar a lista de comandos a seguir no labs play with docker

docker swarm init --advertise-addr (ip do primeiro node)

copiar o docker swarm join --token

colar o token em todos os node

fazer o backup do master usando: docker node promote node2
depois verificar com o docker node list

fazer o clone do git usando o comando: git clone https://github.com/EmersonNunesBatista/docker-main.git
depois verificar usando: ls

cd docker-main/

docker stack deploy -c docker-compose.yml site
docker stack deploy -c docker-compose_1.yml cont1
docker stack deploy -c docker-compose_2.yml cont2
docker stack deploy -c docker-compose_3.yml kuma
