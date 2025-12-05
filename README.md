# xo-nginx

An nginx container and configuration for use with dockerized applications.

## Prerequisites

- Docker
- Docker Compose

## Usage

### Build and Run

```bash
docker compose up -d
```

### Stop

```bash
docker compose down
```

### Rebuild

```bash
docker compose up -d --build
```

## Configuration

- `nginx.conf` - Main nginx configuration file
- `Dockerfile` - Container build instructions
- `docker-compose.yml` - Docker Compose deployment configuration

## Health Check

The nginx server includes a health check endpoint at `/health` that returns a 200 OK response.