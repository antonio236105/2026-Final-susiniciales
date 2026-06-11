# 2026-Final-susiniciales

## Construir imagen de la aplicación

Se le facilita fichero `Dockerfile`.

## Desplegar aplicación y servicios necesarios

Se le facilita fichero `compose.yaml`.

## Probar en local

```sh
$ curl http://localhost
{"message":"FastAPI Antonio Palacios Hernandez version 2.0" }
```

```sh
$ curl http://localhost/db-check
{"status":"Conexión a la base de datos exitosa"}
```

## Probar en AWS tras devops

```sh
$ curl http://IP_AWS
{"message":"FastAPI Antonio Palacios Hernandez version 2.0"}
```

```sh
$ curl http://IP_AWS/db-check
{"status":"Conexión a la base de datos exitosa"}
