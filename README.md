<p align="center"><img src="https://s.w.org/style/images/about/WordPress-logotype-wordmark.png" width="500"></p>

# WordPress Docker
- WordPress v6.4.x
- PHP v8.2.x
- MariaDB v10.x
- MySQL v8.x
- Adminer v4.8.x

# Requirements
- Stable version of [Docker](https://docs.docker.com/engine/install/)
- Compatible version of [Docker Compose](https://docs.docker.com/compose/install/#install-compose)

# How To Deploy
- `docker compose up -d`

# Notes

### WordPress
- URL: http://localhost

### Adminer
- URL: http://localhost:8080
- System: `PostgreSQL`
- Server: `db`
- Username: `refactorian`
- Password: `refactorian`
- Database: `refactorian`

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
