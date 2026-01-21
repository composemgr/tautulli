# Tautulli

A self-hosted application for managing tautulli.

## Installation

### Option 1: Quick Install
```bash
curl -q -LSsf "https://raw.githubusercontent.com/composemgr/tautulli/main/docker-compose.yaml" | docker compose -f - up -d
```

### Option 2: Git Clone
```bash
git clone "https://github.com/composemgr/tautulli" ~/.local/srv/docker/tautulli
cd ~/.local/srv/docker/tautulli
docker compose up -d
```

### Option 3: Using composemgr
```bash
composemgr install tautulli
```

## Configuration

See docker-compose.yaml for environment variables and configuration options.

## Documentation

Check the official project documentation for detailed setup and usage information.
