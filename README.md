Mega-Plex
===================================

### Run
`docker-compose up`
`docker-compose up -d`

### Try it out
- [Organizr](http://localhost)
- [Plex](http://localhost:32400)  
- [Tautulli](http://localhost:8181)
- [Sabnzbd](http://localhost:8080)
- [Ombi](http://localhost:3579)
- [Sonarr](http://localhost:8989)
- [Radarr](http://localhost:7878)

## Useful commands
### List containers
`docker ps`

### SSH into a container
`docker exec -it <container name>`

### Rebuild
`docker-compose build --no-cache`
`docker-compose up --force-recreate --build`

### Clean up
`docker image prune -f`

### Restart a container
`docker-compose restart <container name>`

## List Docker CLI commands
`docker`
`docker container --help`

## Display Docker version and info
`docker --version`
`docker version`
`docker info`

## Execute Docker image
`docker run hello-world`

## List Docker images
`docker image ls`

## List Docker containers (running, all, all in quiet mode)
`docker container ls`
`docker container ls --all`
`docker container ls -aq`
