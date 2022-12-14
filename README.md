# telegraf-node

Telegraf with node support
- 1.23.0 with Node 18
- 1.20.4 with Node 16
- 1.19.3 with Node 16

## Docker Hub

[Found on Docker Hub here](https://hub.docker.com/repository/docker/anujrnair/telegraf-node)

## Build

```
$ docker login
$ docker buildx build --push --platform linux/amd64,linux/arm64 -t anujrnair/telegraf-node:<"latest" | version> .
```
