# Portainer Setups

Use:
```bash
git clone https://github.com/FinchTechSoCal/docker-portainer.git ~/appdata/docker_files/portainer
```

Modify .env, then
```bash
cd ~/appdata/docker_files/portainer
docker compose -f docker-compose-<version>.yml -p portainer up -d
```
