### sart 

```
git clone <url> demo
cd demo


```


### step to build Docker Image

Bulid frontend

```
docker compose build frontend
```

Bulid backend

```
docker compose build backend
```

Bulid All services

```
docker compose build 
```

## Run with docker compose 

```
docker compose up -d database
docker compose up -d backend
docker compose up -d frontend

(check result)

$docker compose ps

```

Tesingwith url :: http://localhost:3000/api/demo