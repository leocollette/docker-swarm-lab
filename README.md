Subir aplicacao:

Para VirtualBox

- vagrant up

ou para Virt-Manager (plugin necessario https://github.com/vagrant-libvirt)

- vagrant up --provider=libvirt

Exportar acesso para manusear o node manager do swarm a partir do host:

- export DOCKER_HOST=IP_SWARM_MANAGER:2375

Deploy aplicacao do Blog:

- docker stack deploy -c docker-compose.blog.yml blog

Deploy aplicacao do Monitoramento:

- docker stack deploy -c docker-compose.observability.yml observability
