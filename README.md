# SelfHosted Container Repository

## Overview

This is collection of useful services and applications in a containerized environment. Whether you're a developer, hobbyist, or just looking to enhance your Raspberry Pi experience, this repository has something for you.

## Getting Started

To get started, make sure you have Docker installed on your Raspberry Pi. If you don't have it installed, you can follow the official [Docker installation guide for Raspberry Pi](https://docs.docker.com/desktop/install/raspberry-pi/).

### Clone the Repository

```bash
git clone https://github.com/diego-ch/selfhosted.git
cd selfhosted
```

### Create the docker network
```
docker network create homelab
```

### Run the Stack
```
docker compose up -d
```