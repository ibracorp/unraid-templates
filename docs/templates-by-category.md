# unRAID Templates by Category

This document provides an overview of all available templates in the IBRACORP unRAID Community Applications Templates Repository, categorized by their primary function.

## Security (9 templates)

### Authelia
**Directory**: `authelia/`  
Open-source authentication and authorization server with 2FA and SSO

### Authentik
**Directory**: `authentik/`  
Open-source Identity Provider focused on flexibility and versatility

### Authentik Worker
**Directory**: `authentik-worker/`  
Worker component for Authentik identity provider

### CrowdSec
**Directory**: `crowdsec/`  
Free, open-source collaborative IPS for behavior analysis and attack response

### CrowdSec Traefik Bouncer
**Directory**: `crowdsec-traefik-bouncer/`  
Bouncer for Traefik to block malicious IPs using CrowdSec

### Docker Socket Proxy
**Directory**: `docker-socket-proxy/`  
Security-enhanced proxy for the Docker Socket

### Pomerium
**Directory**: `pomerium/`  
Identity-aware proxy for secure access to internal applications

### PWM
**Directory**: `pwm/`  
Free password self-service application for enterprise environments

### Zoraxy
**Directory**: `zoraxy/`  
General purpose request (reverse) proxy and forwarding tool

---

## Productivity (28 templates)

### Activepieces
**Directory**: `activepieces/`  
No-code workflow builder with extensible TypeScript framework

### BabyBuddy
**Directory**: `babybuddy/`  
Baby care tracker for sleep, feedings, diaper changes, and tummy time

### Cachet
**Directory**: `cachet/`  
Beautiful open source status page system, replacement for StatusPage.io

### Cachet URL Monitor
**Directory**: `cachet-url-monitor/`  
Python plugin for Cachet to monitor URLs and latency

### Cal.com
**Directory**: `cal-com/`  
Open source Calendly alternative for scheduling

### Casdoor
**Directory**: `casdoor/`  
Open-source, multi-tenant identity and access management (IAM) solution

### Databag
**Directory**: `databag/`  
Federated chat app focused on user privacy and security

### Fasten
**Directory**: `fasten/`  
Secure platform for connecting healthcare providers and personal health records

### Formbricks
**Directory**: `formbricks/`  
In-product micro-surveys solution for enhanced product experience

### Ghost
**Directory**: `ghost/`  
Free open-source blogging platform with MariaDB and SMTP support

### Gitness
**Directory**: `gitness/`  
Lightweight code hosting and continuous integration service

### Homepage
**Directory**: `homepage/`  
Highly customizable homepage with Docker and service API integrations

### Kimai
**Directory**: `kimai/`  
Professional time-tracking application for freelancers and companies

### LinkStack
**Directory**: `linkstack/`  
Self-hosted open-source Linktree alternative

### Matomo
**Directory**: `matomo/`  
Free open-source web analytics application (formerly Piwik)

### OwnCloud OCIS
**Directory**: `owncloud-ocis/`  
Next-generation file sync and share platform built with Go

### Picsur
**Directory**: `picsur/`  
Self-hostable image sharing service like Imgur with built-in converting

### Quant-UX Backend
**Directory**: `quant-ux-backend/`  
Backend for Quant UX research and prototyping tool

### Quant-UX Frontend
**Directory**: `quant-ux-frontend/`  
Frontend for Quant UX research and prototyping tool

### Starbase
**Directory**: `starbase/`  
Nice looking homepage for Docker containers, services and links

### Super Productivity
**Directory**: `super-productivity/`  
ToDo List/Time Tracker/Personal Jira Task Manager

### Timelite
**Directory**: `timelite/`  
Time tracking application for individuals and teams

### Timetagger
**Directory**: `timetagger/`  
Tag-based time tracking tool with interactive UX and reporting

### Traggo
**Directory**: `traggo/`  
Tag-based time tracking tool (no tasks, only tagged time spans)

### Traefik
**Directory**: `traefik/`  
Popular cloud-native application proxy for microservices

### VoceChat Server
**Directory**: `vocechat-server/`  
Lightweight chat server prioritizing private hosting

### Wrapperr
**Directory**: `wrapperr/`  
Plex user stats collection platform using Tautulli (like Spotify Wrapped)

### XWiki
**Directory**: `xwiki/`  
Enterprise wiki with WYSIWYG editing and advanced permissions

### Yacht
**Directory**: `yacht/`  
Web interface for managing Docker containers with templating

---

## Media (6 templates)

### Beatbump
**Directory**: `beatbump/`  
Music listening experience with privacy focus (YouTube alternative)

### Jellyseerr
**Directory**: `jellyseerr/`  
Media request management for Jellyfin & Emby servers

### Muer
**Directory**: `muer/`  
Modern open-source music player based on Invidious/YouTube

### PlexTraktSync
**Directory**: `plextraktsync/`  
Two-way sync between trakt.tv and Plex Media Server

### Serviio
**Directory**: `serviio/`  
DLNA media server for streaming to TVs, Blu-ray players, and devices

### ViewTube
**Directory**: `viewtube/`  
Self-hostable frontend for YouTube

---

## Tools & Other (6 templates)

### DocuSeal
**Directory**: `docuseal/`  
Secure digital document signing and processing platform

### EverShop
**Directory**: `evershop/`  
GraphQL-based React ecommerce platform

### Exercise Diary
**Directory**: `exercise diary/`  
Workout diary with GitHub-style year visualization

### LidaTube
**Directory**: `lidatube/`  
Web GUI for finding and downloading missing Lidarr albums

### Maintainerr
**Directory**: `maintainerr/`  
Media management tool for creating custom rules across services

### Send
**Directory**: `send/`  
File sharing experiment for sending encrypted files

---

## Gaming & Game Servers (2 templates)

### Pterodactyl Daemon
**Directory**: `pterodactyl-daemon/`  
Game server daemon for Pterodactyl panel

### Pterodactyl Panel
**Directory**: `pterodactyl-panel/`  
Open-source game server management panel

---

## Cloud & Business Tools (1 template)

### JIRA Service Desk
**Directory**: `jira-service-desk/`  
Fully featured service desk tool for modern IT teams

---

## Backup & System Management (1 template)

### Unraid Config Guardian
**Directory**: `unraid-config-guardian/`  
Disaster recovery documentation generator for Unraid setups

---

## Uncategorized (1 template)

### Slash
**Directory**: `slash/`  
Bookmarking and short link service with analytics

---

## Repository Statistics

- **Total Templates**: 54
- **Most Popular Category**: Productivity (28 templates)
- **Template Format**: All templates use Container version="2" XML format
- **Installation**: Templates are accessible through the unRAID Community Applications interface

## Template Structure

Each template is organized in its own directory with the following structure:
```
[app-name]/
└── [app-name].xml    # unRAID template XML file
└── [app-name].png    # unRAID template icon file (optional) #Ignore if pulling from another repository
```

Templates can be installed directly from the unRAID Apps interface or accessed via:
```
https://raw.githubusercontent.com/ibracorp/unraid-templates/master/[app-name]/[app-name].xml
```

## Support

- **Discord Community**: https://discord.gg/VWAG7rZ
- **Documentation**: https://docs.ibracorp.io
- **Repository**: https://github.com/ibracorp/unraid-templates