# Reverse Proxy with Docker Swarm + Traefik

## Ferramentas utilizadas
- Docker - execução de containers
- Docker Swarm - Orquestração de containers
- Traefik - Proxy Reverso
- Portainer - Administração de Containers

## Adicionar as seguintes entradas no arquivo host do windows
# C:\Windows\System32\drivers\etc
127.0.0.1	proxy.localhost
127.0.0.1	portainer.localhost
127.0.0.1	postgresdb.localhost
127.0.0.1	rabbitmq.localhost
127.0.0.1	mongodb.localhost
127.0.0.1	backend.localhost
127.0.0.1	whoami.localhost
