# Desafio 01 - Banco de Dados PostgreSQL

Para subir um banco de dados Postgres, com o nome do banco `curso_docker`, usuário `docker_usr` e senha `docker_pwd` basta rodar os seguintes comando

```bash
docker run --name some-postgres -e POSTGRES_PASSWORD=docker_pwd -e POSTGRES_USER=docker_usr -e POSTGRES_DB=curso_docker
 -d postgres
```

# Desafio 02 - Banco de Dados MySQL

Para subir um banco de dados MySQL, com o nome do banco `docker_db`, usuário `docker_usr` e senha `docker_pwd` basta rodar os seguintes comando

```bash
docker run --name some-mysql -e MYSQL_ROOT_PASSWORD=docker_pwd_root -e MYSQL_DATABASE=docker_db -e MYSQL_USER=docker_usr -e MYSQL_PASSWORD=docker_pwd -d mysql
```

# Desafio 03 - Banco de Dados MongoDB

Para subir um banco de dados MongoDB, com o usuário `docker_usr` e senha `docker_pwd` basta rodar os seguintes comando

```bash
docker run --name some-mongo -e MONGO_INITDB_ROOT_USERNAME=mongo_usr -e MONGO_INITDB_ROOT_PASSWORD=mongo_pwd -d mongo
```