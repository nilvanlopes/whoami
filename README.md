# whoami

This repository contains a simple `docker-compose.yml` file to run the `traefik/whoami` service.

## Usage

1.  Create a `.env` file from the `.env.example` file and set the `WHOAMI_HOST` variable.
2.  Run `docker-compose up -d`.

The `whoami` service will be available at the host you specified in the `.env` file.
