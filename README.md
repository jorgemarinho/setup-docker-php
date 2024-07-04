# Setup Docker PHP



## Instruções

Baixa o repositorio

```
git clone https://github.com/jorgemarinho/setup-docker-php
```

Subir o serviço docker, caso não esteja iniciado

```
service docker start
```


Primeira vez, fazer um build

```
docker-compose up --build 
```

Outras vezes
```
docker-compose up -d
```

Serviço disponivel na porta

```
http://localhost:8000
```