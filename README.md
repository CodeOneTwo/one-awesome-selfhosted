# My collection of self-hosted services

basic setup is:

- start `traefik`
- start all `shared_<database>` services
- start all the remaining services

## Start all the services

1. `cd` to the different services
2. edit the `docker-compose.yml` and change <my-domain> and other env vars
3. `docker-compose up -d`

