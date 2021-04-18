[![HA Version](https://img.shields.io/badge/Running%20Home%20Assistant-2021.4.3%20-darkblue)](https://github.com/home-assistant/core/releases/tag/2021.4.3)
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
* [Zigbee2MQTT](https://hub.docker.com/r/koenkk/zigbee2mqtt)
* [Zigbee2MQTTAssistant](https://hub.docker.com/r/carldebilly/zigbee2mqttassistant)

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
  * Xiaomi Aqara Temperature and humidity sensor (Zigbee2MQTT)
  * Xiaomi Aqara Door and Window sensor (Zigbee2MQTT)
* NS (Dutch railways)
* Onvif
* Pi-Hole
* Ping (Netgear ReadyNAS NV+ v2)
* RESTful
  * OpsGenie on call status
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
* [Adax heating](https://github.com/Danielhiversen/home_assistant_adax)
* [Ecowitt](https://github.com/garbled1/homeassistant_ecowitt) - Alecto WS-5500
* [HACS](https://github.com/hacs/integration)
* [iCal](https://github.com/tybritten/ical-sensor-homeassistant)
* [Monitor Docker](https://github.com/ualex73/monitor_docker)
* [Nefit easy](https://github.com/ksya/ha-nefiteasy)

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

## Wishlist
* Xiaomi Mi Flora Plant monitor
* Netgear ReadyNAS
* Samsung TV
* Presence detection
* [DIY cat feeder](https://github.com/AdeZwart/RPi-HomeAutomation)
* Custom integration for underground trash container usage

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