# code-server-docker
code-server on docker with nginx-proxy, acme-companion

## nginx-proxy with ssl
```shell
docker-compose -f nginx-proxy.yaml up -d
```

## code server
```shell
docker-compose -f code-server.yaml up -d
```

## Link
- [code-server](https://hub.docker.com/r/linuxserver/code-server)
- [nginx-proxy](https://github.com/nginx-proxy/nginx-proxy)
- [acme-companion](https://github.com/nginx-proxy/acme-companion)


