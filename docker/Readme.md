# Docker 

### Stop all running images
```bash
docker stop $(docker ps -q) 
``` 

### Remove all images
```bash
docker rmi $(docker images -q) 
``` 

### Get ip addresss of running container
```bash
docker inspect <containerNameOrId> | grep '"IPAddress"'
```


