# Dockerized [`mattes/migrate`](https://github.com/mattes/migrate)

[![Docker Hub](https://img.shields.io/badge/container-ready-blue.svg?style=flat-square)](https://hub.docker.com/r/jeremejevs/mattes-migrate)

```bash
docker run --rm -v $PWD/migrations:/migrations jeremejevs/mattes-migrate -path . -database $DATABASE_URL up
```
