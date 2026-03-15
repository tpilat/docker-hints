# DOCKER


## START 
**Start / Deploy**
```bash
docker compose up -d
```


**Force recreate and Start / Deploy**
```bash
docker compose up -d --force-recreate
```


**Follow `container` logs / stream `container` logs**
```bash
docker logs -f <container>
```


## INSPECT  
**print env values**
```bash
ocker inspect ContainerName --format '{{range .Config.Env}}{{println .}}{{end}}'
```
