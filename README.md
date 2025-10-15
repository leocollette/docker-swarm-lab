Subir aplicacao:

vagrant up --provider=libvirt


docker stack deploy -c docker-compose.blog.yml blog


docker stack deploy -c docker-compose.observability.yml observability


export DOCKER_HOST=IP_SWARM_MANAGER:2375
