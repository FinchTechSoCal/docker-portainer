# Portainer Setups

Use:
```bash
rm -fr ~/appdata/docker_files/portainer
git clone https://github.com/FinchTechSoCal/docker-portainer.git ~/appdata/docker_files/portainer
```

Modify .env, then
```bash
docker compose -f ~/appdata/docker_files/portainer/docker-compose.yml up -d
```

## LTS / STS Differences
[LTS image](https://docs.portainer.io/whats-new#long-term-support-lts)
[STS image](https://docs.portainer.io/sts/whats-new#short-term-support-sts)