# infrastructure-masternode
Infrastructure services for my main homelab node

## Services

- `glances`: `docker compose -f glances/compose.yml up -d` (web UI: `http://<host>:61208`)
- `hermes`: `docker compose -f hermes/compose.yml up -d`
- `n8n`: `docker compose -f n8n/compose.yml up -d`
- `portainer`: `docker compose -f portainer/compose.yml up -d`
- `silverbullet`: `docker compose -f silverbullet/compose.yml up -d`
