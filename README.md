# Postgrest-railway-template

This template provides a minimal setup for running [PostgREST](https://postgrest.org) using Docker. It includes a Postgres database and a PostgREST service configured to expose your database over HTTP.

## Running locally

1. Ensure [Docker](https://www.docker.com/get-started) is installed and running.
2. Start the stack:

   ```sh
   docker-compose up --build
   ```

The PostgREST API will be available at [http://localhost:3000](http://localhost:3000).

## Configuration

The default configuration uses the following credentials for the Postgres database:

- **Database:** `postgres`
- **User:** `postgres`
- **Password:** `postgres`

Update `postgrest.conf` or the environment variables in `docker-compose.yml` to suit your needs.
