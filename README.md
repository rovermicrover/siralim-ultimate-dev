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

[The ui can then be accessed here](http://localhost/)

[The api can then be accessed here](http://localhost/api/)

[API End Points Swagger here](http://localhost/api/docs)

[API End Points Redoc here](http://localhost/api/redoc)

To startup the dev env without the data bootstraping simply run

```bash
$ commands/dev
```

## How To Test

### Requirements

1. Bash

2. git

3. Docker Compose

4. Do setup for dev

### Walk Through To Run UI and API tests

Run

```bash
$ commands/test
```

The API tests than the UI tests will run.

## Commands

1. ```bash $ commands/dev-bootstrap```: Bootstrap the dev env and starts it up

2. ```bash $ commands/dev```: Starts up the dev env

3. ```bash $ commands/dev-nuke```: Destroy the dev env and start over from ground zero

3. ```bash $ commands/test```: Run all the tests

### API Commands

1. ```bash $ commands/api/ci```: Run to check the API in its CI env before build and deploy

2. ```bash $ commands/api/import```: Import game data from files

3. ```bash $ commands/api/lint```: Lint the API code

4. ```bash $ commands/api/lint-check```: Lint the API code and return 0 if lint fails

5. ```bash $ commands/api/migrate```: Run outstanding DB migrations for the API

6. ```bash $ commands/api/test```: Run the API tests

### API Commands

1. ```bash $ commands/ui/ci```: Run to check the UI in its CI env before build and deploy

3. ```bash $ commands/ui/lint```: Lint the UI code

5. ```bash $ commands/ui/format-check```: Format 

6. ```bash $ commands/ui/test```: Run the API tests