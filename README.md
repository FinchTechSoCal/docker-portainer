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
![Static Badge](https://img.shields.io/badge/LTS%20Docs?logo=portainer&link=https%3A%2F%2Fdocs.portainer.io%2Fwhats-new%23long-term-support-lts)

[LTS image](https://docs.portainer.io/whats-new#long-term-support-lts)

[STS image](https://docs.portainer.io/sts/whats-new#short-term-support-sts)