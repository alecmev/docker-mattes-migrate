# Dockerized [`mattes/migrate`](https://github.com/mattes/migrate)

[![Docker Hub](https://img.shields.io/badge/container-ready-blue.svg?style=flat-square)](https://hub.docker.com/r/jeremejevs/migrate)

```bash
docker run --rm -v $PWD/migrations:/workspace jeremejevs/migrate -database $DATABASE_URL up
```
