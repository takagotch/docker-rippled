### docker-rippled
---
https://github.com/WietseWind/docker-rippled

```sh
go/up 8080
docker build --tag rippled:latest .
docker run -dit \
  --name rippled \
  -p 80:80 \
  - /My/Local/Disk/RippledConfig/:/config/ \
  xrptipbot/rippled:latest

docker logs -f rippled
docker exec rippled server_info
```

```
```

```
```


