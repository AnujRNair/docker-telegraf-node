# telegraf-node

Telegraf with node support
- 1.23.0 with Node 18
- 1.20.4 with Node 16
- 1.19.3 with Node 16

## Build

```
$ docker login
$ docker buildx build --push --platform linux/amd64,linux/arm64 -t anujrnair/telegraf-node:<"latest" | version> .
```
