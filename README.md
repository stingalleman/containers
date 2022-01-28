# Docker containers

## Setup

Rename the `.env.example` to `.env` and fill it in. Put the SSL certificates in the [misc/certificates](misc/certificates) folder. Check the README for more details.

Generate a .htpasswd file for HTTP Basic Auth (`htpasswd -c traefik/dynamic/.htpasswd <username>`)

When you're finished, just run

```bash
./compose up -d
```

All URLs, ports and services are documented in [SERVICES.md](SERVICES.md)
