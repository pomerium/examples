# Pomerium as forward-auth provider for Traefik

## Includes

- Authentication and Authorization managed by pomerium
- Certificates managed by LetsEncrypt
- Routing / reverse proxying handled by traefik

## How

- Replace `x.y.z` with your domain in `config.yaml` and `docker-compose.yaml`.
- Replace `you@x.y.z` with your email.
- Replace secrets in `config.yaml`.
- Run `docker-compose up` from this directory.
- Navigate to `https://httpbin.x.y.z`
- ???
- Profit
