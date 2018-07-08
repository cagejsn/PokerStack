# Poker Stack

Angular frontend, Go backend, MySQL db 

## Getting Started

All that you should need to run this is docker.

docker swarm init

docker stack deploy -c stack.yml poker

docker stack rm poker

docker swarm leave --force

