[![HA Version](https://img.shields.io/badge/Running%20Home%20Assistant-2021.1.4%20-darkblue)](https://github.com/home-assistant/core/releases/tag/2021.1.4)
[![Last commit](https://img.shields.io/github/last-commit/AdeZwart/home-assistant-config.svg?style=plasticr")](https://github.com/AdeZwart/home-assistant-config/commits/main)

# Home Assistant configuration

This is an overview of my [home assistant](https://www.home-assistant.io/) setup

## Setup
I'm running [Home Assistant Core in a docker container](https://hub.docker.com/r/homeassistant/raspberrypi3-homeassistant) on my Raspberry Pi 3B+

## Other containers
* [Grafana](https://hub.docker.com/r/grafana/grafana)
* [InfluxDB](https://hub.docker.com/_/influxdb)
* [Mosquitto](https://hub.docker.com/_/eclipse-mosquitto)
* [Pi Hole](https://hub.docker.com/r/pihole/pihole)
* [Portainer](https://hub.docker.com/r/portainer/portainer-ce)
* [Swag (Nginx + Let's encrypt)](https://hub.docker.com/r/linuxserver/swag)

See also my [Docker setup repo](https://github.com/AdeZwart/docker-compose-configuration)

## Tooling
* [VS Code](https://code.visualstudio.com/download)
  * [Home Assistant Config Helper](https://github.com/keesschollaart81/vscode-home-assistant)
  * [Remote - SSH](https://github.com/Microsoft/vscode-remote-release)
* [Windows Terminal](https://github.com/microsoft/terminal)
  * [Dracula theme](https://draculatheme.com/windows-terminal)
  * [SSH](https://docs.microsoft.com/en-us/windows/terminal/tutorials/ssh)

## Devices

### Official integrations
* Buienradar (Dutch weather forecast)
* Camera (Generic IP camera)
* Certificate Expiry
* DSMR Slimme meter (Dutch Smart Meter Requirements)
* Google Chromecast
* Growatt (Inverter for photovoltaic plant)
* Ikea tradfri
* Influx DB
* LG Netcast
* Mobile App (android)
* MQTT
  * Smart doorbell (ESPHome based)
* NS (Dutch railways)
* Onvif
* Pi-Hole
* Ping (Netgear ReadyNAS NV+ v2)
* RFXCOM RFXtrx
  * Somfy RFY sunscreens (2x)
  * Alecto SA-41 smoke detectors (3x)
* Shelly
* Speedtest
* Stookalert
* System monitor
* Telegram
* Utility Meter
* Wake On Lan (Netgear ReadyNAS NV+ v2)
* Xiaomi Miio (Robot Vacuum Roborock S5 Max)
  
### HACS integrations
* Adax heating
* HACS
* iCal
* Monitor Docker
* Nefit easy

### Custom integrations
* -

## Automations
* Notifications for trash collection
* Front door light (evening, morning and when coming home while dark)
* Central heating pressure notifications (low & high)
* System monitor temperature notifications
* Lighting adjustment when streaming on the living room Chrome Cast
* Manually triggered bed-time routine
* Actionable notification reminder to have the Roborock report at the trashbin to empty the dustbin
* Send a camera snapshot to Telegram when the doorbell is pressed

## Wishlist
* Netgear ReadyNAS (Rest API?)
* Door sensors
* Samsung TV
* Xiaomi Aqara Temperature Humidity Sensors
* Motion sensors
* [DIY cat feeder](https://github.com/AdeZwart/RPi-HomeAutomation)
* Custom integration for underground trash container usage
* Ops Genie OnCall status

## Tutorials I've used
* [BurnsHA](https://www.youtube.com/c/BurnsHA)
  * [Installing Home Assistant in Docker](https://youtu.be/bG6g2btJbNk)
  * [InfluxDB, Grafana & Home Assistant - Pt 1.](https://youtu.be/lveSI3hPHE8)
  * [InfluxDB, Grafana & Home Assistant - Pt 2.](https://youtu.be/rMaU69am_cg)
  * [Pi-hole, Add-blocks and Home Assistant](https://youtu.be/yMbpxB39X1Y)
  * [LetsEncrypt with NginX for Home Assistant](https://youtu.be/oN1qPl3Yve8)
* [Frenck - DIY smart doorbell for just 2 dollar](https://frenck.dev/diy-smart-doorbell-for-just-2-dollar/)

## A curated list of awesome Home Assistant resources
[Awesome Home Assistant](https://www.awesome-ha.com/)