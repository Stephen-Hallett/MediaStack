## This was yoinked almost entirely from [geekau/mediastack](https://github.com/geekau/mediastack)

### Requirements
- docker
- docker-compose

### To run:
Configure docker-compose-template.env & rename to docker-compose.env
```sh
git clone https://github.com/Stephen-Hallett/MediaStack.git
cd MediaStack
# CONFIGURE docker-compose.env

docker compose --env-file docker-compose.env up -d
```