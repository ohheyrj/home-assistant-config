# Home Assistant Config

[![Home Assistant CI - Configuration Checks](https://github.com/rj175/home-assistant-config/actions/workflows/main.yml/badge.svg)](https://github.com/rj175/home-assistant-config/actions/workflows/main.yml)
[![Home Assistant CI - Linting](https://github.com/rj175/home-assistant-config/actions/workflows/linting.yml/badge.svg)](https://github.com/rj175/home-assistant-config/actions/workflows/linting.yml)
[![HA Version](https://img.shields.io/badge/Home%20Assistant-2021.10.6-brightgreen)](https://github.com/home-assistant/home-assistant/releases/2021.10.6)

This is my Home Assistant installation.

## Entities

Below is a break down of the different types of entities that are currently deployed within my HA instance.

### Devices

Camera | Device Tracker | Light | Media Player | Switch
-- | -- | -- | -- | --
4 | 29 | 22 | 12 | 13

### Inputs

Boolean | Datetime | Number | Select | Text
-- | -- | -- | -- | --
11 | 0 | 5 | 5 | 0

### People & Places

Person | Zone
-- | --
2 | 5

### Sensors

Binary Sensors | Sensors
-- | --
40 | 138

### Other

Alert | Automation | Group | Scene | Script
-- | -- | -- | -- | --
1 | 34 | 4 | 20 | 4

## HACS

In addition to the pre-installed integrations and lovelace cards, HACS is used to managed and install additional
functionality.

### Integrations
Name | Description | Installed Version | Documentation
 --- | ----------- | ----------------- | -------------
Alexa Media Player | This is a custom component to allow control of Amazon Alexa devices in Home Assistant using the unofficial Alexa API. | v3.10.10 | https://github.com/custom-components/alexa_media_player
Amazon Rekognition | Home Assistant Object detection with Amazon Rekognition | v3.1 | https://github.com/robmarkcole/HASS-amazon-rekognition
Authenticated | A platform which allows you to get information about sucessfull logins to Home Assistant. | 21.9.0 | https://github.com/custom-components/authenticated
Aws Codepipeline | An integration to monitor and execute AWS Codepipeline projects within Home Assistant. | v1.0.0 | https://github.com/rj175/home-assistant-aws-codepipeline
Generate Readme | Use Jinja and data from Home Assistant to generate your README.md file | 0.3.0 | https://github.com/custom-components/readme
Google Home | Home Assistant Google Home custom component  | v1.8.2 | https://github.com/leikoilja/ha-google-home
Govee | A HACS repository for Govee light integration | 0.2.1 | https://github.com/LaggAt/hacs-govee
HACS | HACS gives you a powerful UI to handle downloads of all your custom needs. | 1.15.2 | https://github.com/hacs/integration
Homeassistant Virgintivo | HomeAssistant component for control of Virgin Media Tivo boxes | 0.1.23 | https://github.com/bertbert72/HomeAssistant_VirginTivo
Hp Printers Integration | HP Printer Integration | 1.0.1 | https://github.com/elad-bar/ha-hpprinter
Node Red Companion | Companion Component for node-red-contrib-home-assistant-websocket to help integrate Node-RED with Home Assistant Core | v0.5.2 | https://github.com/zachowj/hass-node-red
Spotcast | Home assistant custom component to start Spotify playback on an idle chromecast device as well as control spotify connect devices | v3.6.17 | https://github.com/fondberg/spotcast
Tapo: Cameras Control | Control for Tapo cameras as a Home Assistant component | 3.4.1 | https://github.com/JurajNyiri/HomeAssistant-Tapo-Control
Tuya V2 | Home Assistant integration for controlling Powered by Tuya (PBT) devices using Tuya Open API, maintained by the Home Assistant Community and Tuya Developer Team. | v1.6.0 | https://github.com/tuya/tuya-home-assistant

### Lovelace
Name | Description | Installed Version | Documentation
 --- | ----------- | ----------------- | -------------
Auto Entities | 🔹Automatically populate the entities-list of lovelace cards | 1.9.1 | https://github.com/thomasloven/lovelace-auto-entities
Button Card | ❇️ Lovelace button-card for home assistant | v3.4.2 | https://github.com/custom-cards/button-card
Github Card | Track your repo issues, starts, forks, and pull requests | 1.4.1 | https://github.com/ljmerza/github-card
Layout Card | 🔹 Get more control over the placement of lovelace cards. | 2.3.1 | https://github.com/thomasloven/lovelace-layout-card
Mini Graph Card | Minimalistic graph card for Home Assistant Lovelace UI | v0.10.0 | https://github.com/kalkih/mini-graph-card
Slider Button Card | A button card with integrated slider | v1.10.3 | https://github.com/mattieha/slider-button-card
Vertical Stack In Card | 📐 Home Assistant Card: Similar to vertical/horizontal-stack, but removes card borders | v0.4.1 | https://github.com/ofekashery/vertical-stack-in-card

### Addon Repositories
- https://github.com/Apipa169/Assistant-Relay-for-Hassio
- https://github.com/danielwelch/hassio-zigbee2mqtt
- https://github.com/Forceu/barcodebuddy-homeassistant
- https://github.com/gdrapp/hass-addons
- https://github.com/hassio-addons/repository
- https://github.com/lolouk44/hassio-addons
- https://github.com/mdegat01/hassio-addons-edge
- https://github.com/Sabuto/hassio-repo


***

Generated by the [custom readme integration](https://github.com/custom-components/readme)