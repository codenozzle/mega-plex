#Mega-Plex
===================================

### Build
`docker-compose build`

### Run
`docker-compose up`

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

### Clean up
`docker image prune`

### Restart a container
`docker-compose restart <container name>`
