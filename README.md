# Personal Self-Hosted Ecosystem

A complete self-hosted personal cloud ecosystem built with Docker Compose, running 7 applications across 8 containers.

## Services

| Service | Description | Port |
|---------|-------------|------|
| Nextcloud | Personal Google Drive | 8080 |
| Joplin Server | Personal Notion | 8081 |
| Vaultwarden | Personal Password Manager | 8082 |
| Navidrome | Personal Spotify | 4533 |
| Uptime Kuma | Monitoring Dashboard | 3001 |
| MariaDB | Nextcloud Database | internal |
| PostgreSQL | Joplin Database | internal |

## Tech Stack

- Docker & Docker Compose
- Ubuntu 22.04 (WSL2 / AWS EC2)
- Nginx Reverse Proxy (Phase 3)
- Let's Encrypt SSL (Phase 3)
- AWS EC2 (Phase 2)

## Phases

- [x] Phase 1 — Local Docker setup
- [ ] Phase 2 — AWS EC2 deployment
- [ ] Phase 3 — Domain + SSL + Nginx
- [ ] Phase 4 — Monitoring + Automation

## Author

Dhanesh Warekar — github.com/DhaneshWarekar
