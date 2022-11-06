[![HA Version](https://img.shields.io/badge/Running%20Home%20Assistant-2022.11.1%20-darkblue)](https://github.com/home-assistant/core/releases/tag/2022.11.1)
[![Last commit](https://img.shields.io/github/last-commit/AdeZwart/home-assistant-config.svg?style=plasticr")](https://github.com/AdeZwart/home-assistant-config/commits/main)

# Home Assistant configuration

This is an overview of my [home assistant](https://www.home-assistant.io/) setup

## Setup
I'm running [Home Assistant Core in a docker container](https://hub.docker.com/r/homeassistant/raspberrypi3-homeassistant) on my Raspberry Pi 3B+

## Other containers
* [AppDaemon](https://hub.docker.com/r/acockburn/appdaemon)
* [Duck DNS](https://github.com/linuxserver/docker-duckdns)
* [Mosquitto](https://hub.docker.com/_/eclipse-mosquitto)
* [Pi Hole](https://hub.docker.com/r/pihole/pihole)
* [Portainer](https://hub.docker.com/r/portainer/portainer-ce)
* [Swag (Nginx + Let's encrypt)](https://github.com/linuxserver/docker-swag)
* [Wireguard](https://github.com/linuxserver/docker-wireguard)
* [Zigbee2MQTT](https://hub.docker.com/r/koenkk/zigbee2mqtt)

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
* Adax
* Buienradar (Dutch weather forecast)
* Brother Printer
* Camera (Generic IP camera)
* Certificate Expiry
* CO2 Signal
* DNSIP
* DSMR Slimme meter (Dutch Smart Meter Requirements)
* ESPHome
  * Smart doorbell
  * MiFlora plant sensor reading
* Forecast Solar
* Google Chromecast
* Growatt (Inverter for photovoltaic plant)
* LG Netcast
* Mobile App (android)
* MQTT (Zigbee2MQTT)
  * Xiaomi Aqara Temperature and humidity sensor
  * Xiaomi Aqara Door and Window sensor
  * Blitzwolf BW-SHP13
  * Ikea tradfri devices
* NS (Dutch railways)
* Onvif
* Plant
* Pi-Hole
* Ping (Netgear ReadyNAS NV+ v2)
* RFXCOM RFXtrx
  * Somfy RFY sunscreens (2x)
  * Alecto SA-41 smoke detectors (3x)
* Shelly
* Stookalert
* Sure Petcare
* System monitor
* Telegram
* Utility Meter
* Wake On Lan (Netgear ReadyNAS NV+ v2)
* Xiaomi Miio (Robot Vacuum Roborock S5 Max)

### HACS integrations
* [Ecowitt](https://github.com/garbled1/homeassistant_ecowitt) - Alecto WS-5500
* [HACS](https://github.com/hacs/integration)
* [iCal](https://github.com/tybritten/ical-sensor-homeassistant)
* [Monitor Docker](https://github.com/ualex73/monitor_docker)
* [Nefit easy](https://github.com/ksya/ha-nefiteasy)
* [Neerslag App](https://github.com/aex351/home-assistant-neerslag-app)
* [Xiaomi cloud map extractor](https://github.com/PiotrMachowski/Home-Assistant-custom-components-Xiaomi-Cloud-Map-Extractor)

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
* Send a push notification when my phone is set to silent while being on call
* Raise the sunscreens in case of rain or on sunset

## Wishlist
* Presence detection

## Tutorials/Guides/Tools used
* [BurnsHA](https://www.youtube.com/c/BurnsHA)
  * [Installing Home Assistant in Docker](https://youtu.be/bG6g2btJbNk)
  * [InfluxDB, Grafana & Home Assistant - Pt 1.](https://youtu.be/lveSI3hPHE8)
  * [InfluxDB, Grafana & Home Assistant - Pt 2.](https://youtu.be/rMaU69am_cg)
  * [Pi-hole, Add-blocks and Home Assistant](https://youtu.be/yMbpxB39X1Y)
  * [LetsEncrypt with NginX for Home Assistant](https://youtu.be/oN1qPl3Yve8)
* [Frenck - DIY smart doorbell for just 2 dollar](https://frenck.dev/diy-smart-doorbell-for-just-2-dollar/)
* [BeardedTinker - Zigbee2MQTT in Docker](https://www.youtube.com/watch?v=HbkXQErileU)
* [NotEnoughTECH - Flashing CC2531 without CC Debugger](https://www.youtube.com/watch?v=RguRQUXWLCY)
* [Xiaomi cloud tokens extractor](https://github.com/PiotrMachowski/Xiaomi-cloud-tokens-extractor)

## A curated list of awesome Home Assistant resources
[Awesome Home Assistant](https://www.awesome-ha.com/)
