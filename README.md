# Portainer Setups

Use:
```bash
cd /path/to/portainer_type
curl -Ls https://raw.githubusercontent.com/FinchTechSoCal/docker-portainer/main/docker-compose<-agent>.yml -o docker-compose.yaml # <-- match type! -agent, -be, or remove for CE version
curl -Ls https://raw.githubusercontent.com/FinchTechSoCal/docker-portainer/main/.env -o .env
```

Modify .env, then
```bash
docker compose up -d
```