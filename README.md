home-assistant
--------------

This repository contains the configuration for my home automation platform, built on [Home Assistant](https://www.home-assistant.io/).

Requirements
============
* Docker
* Docker Compose

## Installation
Assuming you have overriden the appropriate environment variables in the `.env` file, you can deploy with the usual:

  `docker-compose up -d`

This will deploy Home Assistant as well as a [Caddy](https://caddyserver.com/) reverse proxy with SSL enabled.
