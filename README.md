# SelfHosted Container Repository

## Overview
This is collection of useful services and applications in a containerized environment. Whether you're a developer, hobbyist, or just looking to enhance your container experience, this repository has something for you.

## Table of Contents
- [Getting Started](#getting-started)
- [Containers](#containers)
  - [Dashboards](#dashboards)
  - [DNS](#dns)
  - [Reverse Proxies](#reverse-proxies)
  - [Monitoring](#monitoring)

## Getting Started
To get started, make sure you have Docker installed on your machine.
If you don't have it installed, you can follow the official [Docker Get Started Guide](https://docs.docker.com/get-docker/).

```
# clone the repository
git clone https://github.com/diego-ch/selfhosted.git
cd selfhosted

# create the docker network
docker network create homelab

# run the stack
docker compose up -d
```

## Containers

### Dashboards
**[Homepage](https://github.com/gethomepage/homepage)** - A highly customizable homepage (or startpage / application dashboard) with Docker and service API integrations.

### DNS
**[AdGuardHome](https://github.com/AdguardTeam/AdGuardHome)** - AdGuard Home is a network-wide software for blocking ads and tracking.

### Reverse Proxies
**[Nginx Proxy Manager](https://github.com/NginxProxyManager/nginx-proxy-manager)** - NPM enables you to easily forward to your websites running at home or otherwise, including free SSL, without having to know too much about Nginx or Letsencrypt.

### Monitoring
**[OpenSpeedTest](https://github.com/openspeedtest/Speed-Test)** - HTML5 Network Performance Estimation Tool Written in Vanilla Javascript.

**[Uptime Kuma](https://github.com/louislam/uptime-kuma)** - Uptime Kuma is an easy-to-use self-hosted monitoring tool.

