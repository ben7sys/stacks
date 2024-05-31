# Dockge
https://github.com/louislam/dockge

## Create directories that store your stacks and stores Dockge's stack
mkdir -p /opt/stacks /opt/dockge
cd /opt/dockge

Or any other custom path:
/home/sieben/stacks

## Download the compose.yaml
curl https://raw.githubusercontent.com/louislam/dockge/master/compose.yaml --output compose.yaml

## Start the server
docker compose up -d

If you are using docker-compose V1 or Podman
```bash
    docker-compose up -d
```

# How to Update

```bash
    cd /opt/dockge
    docker compose pull && docker compose up -d
```


