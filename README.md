# My Glance

My personal [Glance](https://github.com/glanceapp/glance) dashboard config.

## What's inside

| File | Description |
|------|-------------|
| `glance/docker-compose.yml` | Docker Compose to run Glance |
| `glance/config/glance.yml` | Main config, includes pages |
| `glance/config/home.yml` | Dashboard pages (Home, Homelab, Gaming) |
| `glance/icons/` | Custom icons |

### Pages

- **Home** – Search bar, calendar, service monitors, Twitch channels, YouTube videos, weather
- **Homelab** – Minecraft server status, CasaOS monitor
- **Gaming** – Twitch top games, Reddit feeds, gaming YouTube channels

## Usage

```bash
docker compose -f glance/docker-compose.yml up -d
```

Then open http://localhost:2020

## Links

- GitHub: https://github.com/glanceapp/glance
