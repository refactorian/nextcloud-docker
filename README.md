<p align="center"><img src="https://nextcloud.com/c/uploads/2023/02/logo_nextcloud_white.svg" width="300"></p>

# Nextcloud Docker
- Nextcloud v28.x
- Postgres v16.x

# Requirements
- Stable version of [Docker](https://docs.docker.com/engine/install/)
- Compatible version of [Docker Compose](https://docs.docker.com/compose/install/#install-compose)

# How To Deploy
- `docker compose up -d`

# Notes

### Nextcloud App
- URL: http://localhost

### Docker compose commands
- Build or rebuild services
    - `docker compose build`
- Create and start containers
    - `docker compose up -d`
- Stop and remove containers, networks
    - `docker compose down`
- Stop all services
    - `docker compose stop`
- Restart service containers
    - `docker compose restart`
- Run a command inside a container
    - `docker compose exec [container] [command]`
