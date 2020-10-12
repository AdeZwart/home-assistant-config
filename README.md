[![HA Version](https://img.shields.io/badge/Running%20Home%20Assistant-0.116.2%20-darkblue)](https://github.com/home-assistant/core/releases/tag/0.116.2)

# Home Assistant configuration

This is an overview of my [home assistant](https://www.home-assistant.io/) setup

## Setup
I'm running [Home Assistant Core in a docker container](https://hub.docker.com/r/homeassistant/raspberrypi3-homeassistant) on my Raspberry Pi 3B+

## Other containers
* [Grafana](https://hub.docker.com/r/grafana/grafana)
* [InfluxDB](https://hub.docker.com/_/influxdb)
* [Pi Hole](https://hub.docker.com/r/pihole/pihole)
* [Portainer](https://hub.docker.com/r/portainer/portainer-ce)
* [Swag (Nginx + Let's encrypt)](https://hub.docker.com/r/linuxserver/swag)

See also my [Docker setup repo](https://github.com/AdeZwart/docker-setup)

## Tooling
* [VS Code](https://code.visualstudio.com/download)
  * [Home Assistant Config Helper](https://github.com/keesschollaart81/vscode-home-assistant)
  * [Remote - SSH](https://github.com/Microsoft/vscode-remote-release)
* [Windows Terminal](https://github.com/microsoft/terminal)
  * [Dracula theme](https://draculatheme.com/windows-terminal)
  * [SSH](https://docs.microsoft.com/en-us/windows/terminal/tutorials/ssh)

## Devices

### Official integrations
* Buienradar
* Certificate Expiry
* DSML Slimme meter (Dutch Smart Meter Requirements)
* Google Chromecast
* Growatt solar panels
* Ikea tradfri
* Influx DB
* LG Netcast
* Mobile App (android)
* NS (Dutch railways)
* Onvif
* Pi-Hole
* Speedtest
* Stookalert
* System monitor
* Telegram

### HACS integrations
* Adax heating
* HACS
* iCal
* Nefit easy

### Custom integrations

## Automations
* Notifications for trash collection
* Front door light (evening and morning)
* Central heating pressure notifications
* System monitor temperature notifications

## Wishlist
* Roborock S5 Max integration
* Somfy sunscreen control (433mhz)
* Smoke detector integration (433mhz)
* Shelly 1 and 2.5
* Shelly door sensors
* Xiaomi Aqara Temperature Humidity Sensors
* [DIY cat feeder](https://github.com/AdeZwart/RPi-HomeAutomation)
* Custom integration for trash bin usage

## Tutorials I've used
* [BurnsHA](https://www.youtube.com/c/BurnsHA)
  * [Installing Home Assistant in Docker](https://youtu.be/bG6g2btJbNk)
  * [InfluxDB, Grafana & Home Assistant - Pt 1.](https://youtu.be/lveSI3hPHE8)
  * [InfluxDB, Grafana & Home Assistant - Pt 2.](https://youtu.be/rMaU69am_cg)
  * [Pi-hole, Add-blocks and Home Assistant](https://youtu.be/yMbpxB39X1Y)
  * [LetsEncrypt with NginX for Home Assistant](https://youtu.be/oN1qPl3Yve8)

## A curated list of awesome Home Assistant resources
[Awesome Home Assistant](https://www.awesome-ha.com/)