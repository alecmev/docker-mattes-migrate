# Dockerized [`mattes/migrate`](https://github.com/mattes/migrate)

[![Docker Hub](https://img.shields.io/badge/container-ready-blue.svg?style=flat-square)](https://hub.docker.com/r/jeremejevs/mattes-migrate)

### v3 usage

```bash
docker run --rm -v $PWD/migrations:/migrations jeremejevs/mattes-migrate -path . -database $DATABASE_URL up
```

### v1 usage

```bash
docker run --rm -v $PWD/migrations:/migrations jeremejevs/mattes-migrate:1 -url $DATABASE_URL up
```
