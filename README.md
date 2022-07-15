# telegraf-node

Telegraf with node support
- 1.23.0 with Node 18
- 1.20.4 with Node 16
- 1.19.3 with Node 16

## Build

```
$ docker login

$ docker buildx build --platform linux/amd64,linux/arm64 -t telegraf-node:latest .
$ docker tag telegraf-node:latest telegraf-node:<telegraf-version>

$ docker tag telegraf-node:latest anujrnair/telegraf-node:latest
$ docker tag telegraf-node:<telegraf-version> anujrnair/telegraf-node:<telegraf-version>

$ docker push anujrnair/telegraf-node:latest
$ docker push anujrnair/telegraf-node:<telegraf-version>
```
