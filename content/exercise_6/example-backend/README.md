# backend-example-docker

This project is created to help learn docker configurations for backend projects. Student has to figure out how to construct their configuration based on the README. However, there are some additional helpers added in the README and in the exercise description.

# Prerequisites for development

Install [golang](https://golang.org/doc/install) 1.16

# Build project #

Run `go build`. It will generate a binary named "server"

# Test project #

Run tests with `go test ./...`.

# Execute project #

Execute the file e.g. `./server`.

Server accepts the following environment variables:

- `PORT` to choose which port for the application. Default: 8080
- `REQUEST_ORIGIN` to pass an url through the cors check. Default: https://example.com
- `POSTGRES_HOST` The hostname for postgres database. (port will default to 5432 the default for Postgres)
- `POSTGRES_USER` database user. Default: postgres
- `POSTGRES_PASSWORD` database password. Default: postgres
- `POSTGRES_DATABASE` database name. Default: postgres

Note that if this backend is running inside a Docker container and tries to reach the PostgresDB running into another local container, the `POSTGRES_HOST` will be `host.docker.internal`. In case of containers running in a Docker Compose network, you can use the services names.