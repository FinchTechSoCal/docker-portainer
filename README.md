# Portainer Setups

Use:
```bash
rm -fr ~/appdata/docker_files/portainer
git clone https://github.com/FinchTechSoCal/docker-portainer.git ~/appdata/docker_files/portainer
```

Modify .env, then
```bash
cd ~/appdata/docker_files/portainer
docker compose -f ~/appdata/docker_files/portainer/docker-compose-<version>.yml up -d
```
