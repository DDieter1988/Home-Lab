# Services

### This document provides an inventory of the self-hosted services running in the homelab, including their purpose, hosting location, storage dependencies, accessibility, and authentication methods.

| Service | Purpose | Runs On | Storage | Accessible Via | Authenication |
|---------|---------|----------|----------|---------|---------|
| Jellyfin | Media streaming | ompute | edroom | LAN, WAN | Jellyfin Accounts |
| Immich | Photo & video backup | ompute | edroom | LAN, WireGuard | Immich Accounts |
| Seerr | Media request & management | ompute | — | LAN, WAN | Jellyfin SSO |
| Sonarr | TV library automation | ompute | edroom | LAN, WireGuard | Local Account |
| Radarr | Movie library automation | ompute | edroom | LAN, WireGuard | Local Account |
| Prowlarr | Indexer management | ompute | — | LAN, WireGuard | Local Account |
| NZBGet | Usenet download client | ompute | edroom | LAN, WireGuard | Local Account |
| Game Servers | Multiplayer game hosting | edroom | edroom | LAN, WAN | Game-Specific |

## Notes

- All services are containerized using Docker.
- Media and persistent application data are stored on the storage node (`edroom`) and mounted by the compute node (`ompute`) as needed.
- Publicly accessible services are exposed through a DDNS hostname.
