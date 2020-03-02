# MineMeld

Docker deployment with Docker Swarm

    git clone git@github.com:ish1301/minemeld-docker.git
    cd minemeld-docker
    docker swarm init
    docker stack deploy -c docker-compose.yml minemeld

You have minemeld running at https://localhost:6060 (*you may change port in `docker-compose.yml` file*)
