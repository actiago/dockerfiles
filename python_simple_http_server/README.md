# Simple http server

## Executando em seu dispositivo

```bash
cd python_simple_http_server
docker-compose up -d
```

## Testando localmente

Em seu navegador acesse _http://localhost:8888_

Via curl:

```bash
curl localhost:8888/file.txt
```

## Baixando determinado arquivo a partir de um dispositivo remoto

```bash
curl -O hostname_do_servidor:8888/file.txt
```

## Versão
0.1.1
