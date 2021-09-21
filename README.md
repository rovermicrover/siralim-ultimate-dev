# Siralim Ultimate Dev

## About

Compising Dev Repo for [siralim-ultimate-api](https://github.com/rovermicrover/siralim-ultimate-api)

## How To Dev

### Requirements

1. Bash

2. git

3. Docker Compose

### Walk Through To Get Dev ENV Started

Run

```bash
$ commands/dev-bootstrap
```

This will pull all services from their repos, bootstrap all their data, and then start running them via docker compose.

All app files are synced via docker-compose so you can just start deving and changes will show up automatically

[The app can then be accessed here](http://localhost/api/)

[API End Points Swagger here](http://localhost/api/docs)

[API End Points Redoc here](http://localhost/api/redoc)