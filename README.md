# telegraf-node

Telegraf with node support

```
$ docker login

$ docker buildx build --platform linux/amd64 -t telegraf-node:latest .
// $ docker build -t telegraf-node:latest .
$ docker tag telegraf-node:latest telegraf-node:<telegraf-version>

$ docker tag telegraf-node:latest anujrnair/telegraf-node:latest
$ docker tag telegraf-node:<telegraf-version> anujrnair/telegraf-node:<telegraf-version>

$ docker push anujrnair/telegraf-node:latest
$ docker push anujrnair/telegraf-node:<telegraf-version>
```
