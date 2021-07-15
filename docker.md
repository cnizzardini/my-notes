# Docker

[Docker Swarm](https://dockerswarm.rocks/) - how-to's on docker swarm.

Export an image to a tar file:

```console
docker save <IMAGE>:<TAG> -o <NAME>.tar
```

Load an image from a tar:

```console
docker load -i <NAME>.tar 
```
