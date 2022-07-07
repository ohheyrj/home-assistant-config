# Home Assistant Config

[![Home Assistant CI - Configuration Checks](https://github.com/rj175/home-assistant-config/actions/workflows/main.yml/badge.svg)](https://github.com/rj175/home-assistant-config/actions/workflows/main.yml)
[![Home Assistant CI - Linting](https://github.com/rj175/home-assistant-config/actions/workflows/linting.yml/badge.svg)](https://github.com/rj175/home-assistant-config/actions/workflows/linting.yml)
[![HA Version](https://img.shields.io/badge/Home%20Assistant-unavailable-brightgreen)](https://github.com/home-assistant/home-assistant/releases/unavailable)

This is my Home Assistant installation.

## Entities

Below is a break down of the different types of entities that are currently deployed within my HA instance.

### Devices

Camera | Device Tracker | Light | Media Player | Switch
-- | -- | -- | -- | --
6 | 50 | 21 | 28 | 37

### Inputs

Boolean | Datetime | Number | Select | Text
-- | -- | -- | -- | --
24 | 0 | 4 | 10 | 5

### People & Places

Person | Zone
-- | --
2 | 8

### Sensors

Binary Sensors | Sensors
-- | --
58 | 386

### Other

Alert | Automation | Group | Scene | Script
-- | -- | -- | -- | --
6 | 62 | 15 | 19 | 3

## HACS

In addition to the pre-installed integrations and lovelace cards, HACS is used to managed and install additional
functionality.

### Integrations
Name | Description | Installed Version | Documentation
 --- | ----------- | ----------------- | -------------
Alexa Media Player | This is a custom component to allow control of Amazon Alexa devices in Home Assistant using the unofficial Alexa API. | v4.0.2 | https://github.com/custom-components/alexa_media_player
Amazon Rekognition | Home Assistant Object detection with Amazon Rekognition | v3.2 | https://github.com/robmarkcole/HASS-amazon-rekognition
Authenticated | A platform which allows you to get information about sucessfull logins to Home Assistant. | 21.9.0 | https://github.com/custom-components/authenticated
Aws Codepipeline | An integration to monitor and execute AWS Codepipeline projects within Home Assistant. | v1.0.0 | https://github.com/ohheyrj/home-assistant-aws-codepipeline
Browser Mod | 🔹 A Home Assistant integration to turn your browser into a controllable entity - and also an audio player | 1.5.3 | https://github.com/thomasloven/hass-browser_mod
Fontawesome | 🔹 Use icons from fontawesome in home-assistant | 2.1.5 | https://github.com/thomasloven/hass-fontawesome
Generate Readme | Use Jinja and data from Home Assistant to generate your README.md file | 0.5.0 | https://github.com/custom-components/readme
Google Home | Home Assistant Google Home custom component  | v1.9.12 | https://github.com/leikoilja/ha-google-home
Govee | A HACS repository for Govee light integration | 0.2.2 | https://github.com/LaggAt/hacs-govee
HACS | HACS gives you a powerful UI to handle downloads of all your custom needs. | 1.25.5 | https://github.com/hacs/integration
Homeassistant Virgintivo | HomeAssistant component for control of Virgin Media Tivo boxes | 0.1.24 | https://github.com/bertbert72/HomeAssistant_VirginTivo
Hp Printers Integration | HP Printer Integration | v1.0.8 | https://github.com/elad-bar/ha-hpprinter
Icloud3 Device Tracker | iCloud3 - An advanced device_tracker custom_component for iPhones, iPads, etc. It monitors zone & location updates triggered by the HA iOS App and supports Apple 2fa verification. | v2.4.7 | https://github.com/gcobb321/icloud3
Node Red Companion | Companion Component for node-red-contrib-home-assistant-websocket to help integrate Node-RED with Home Assistant Core | v1.0.8 | https://github.com/zachowj/hass-node-red
Spotcast | Home assistant custom component to start Spotify playback on an idle chromecast device as well as control spotify connect devices | v3.6.29 | https://github.com/fondberg/spotcast
Tapo: Cameras Control | Control for Tapo cameras as a Home Assistant component | 3.6.0 | https://github.com/JurajNyiri/HomeAssistant-Tapo-Control
Tuya V2 | Home Assistant integration for controlling Powered by Tuya  (PBT) devices using Tuya Open API, maintained by the Home Assistant Community and Tuya Developer Team. | v1.6.0 | https://github.com/tuya/tuya-home-assistant
Ui Lovelace Minimalist | UI-Lovelace-Minimalist is a "theme" for HomeAssistant | v0.0.9 | https://github.com/UI-Lovelace-Minimalist/UI
Watchman | Home Assistant custom integration to keep track of missing entities and services in your config files | v0.6.0 | https://github.com/dummylabs/thewatchman

### Lovelace
Name | Description | Installed Version | Documentation
 --- | ----------- | ----------------- | -------------
Auto Entities | 🔹Automatically populate the entities-list of lovelace cards | 1.11.0 | https://github.com/thomasloven/lovelace-auto-entities
Bar Card | Customizable Animated Bar card for Home Assistant Lovelace | 3.2.0 | https://github.com/custom-cards/bar-card
Battery State Card / Entity Row | Battery state card for Home Assistant | v2.1.1 | https://github.com/maxwroc/battery-state-card
Button Card | ❇️ Lovelace button-card for home assistant | v3.4.2 | https://github.com/custom-cards/button-card
Card Mod | 🔹 Add CSS styles to (almost) any lovelace card | 3.1.4 | https://github.com/thomasloven/lovelace-card-mod
Card Tools | 🔹A collection of tools for other lovelace plugins to use | 11 | https://github.com/thomasloven/lovelace-card-tools
Flipdown Timer Card | Flipdown Timer Card for Home Assistant Lovelace | v0.11 | https://github.com/pmongloid/flipdown-timer-card
Github Card | Track your repo issues, starts, forks, and pull requests | 1.4.1 | https://github.com/ljmerza/github-card
Layout Card | 🔹 Get more control over the placement of lovelace cards. | 2.4.2 | https://github.com/thomasloven/lovelace-layout-card
Light Popup Card (Homekit Style) | Lovelace card to use as custom pop-up for light in homekit style | 0.5.1 | https://github.com/DBuit/light-popup-card
Mini Graph Card | Minimalistic graph card for Home Assistant Lovelace UI | v0.11.0 | https://github.com/kalkih/mini-graph-card
Mini Media Player | Minimalistic media card for Home Assistant Lovelace UI | v1.16.4 | https://github.com/kalkih/mini-media-player
More Info Card | 🔹 Display the more-info dialog of any entity as a lovelace card | None | https://github.com/thomasloven/lovelace-more-info-card
My Cards Bundle | Bundle of my custom Lovalace cards for Home Assistant. Includes: my-slider | None | https://github.com/AnthonMS/my-cards
Person | Minimalist plugin which allows users to add person entity in order to show the location with a beutiful and clean interface. | v0.8.0 | https://github.com/gerardag/person-entity-card
Search Card | Quickly search for entities from a Lovelace card. | None | https://github.com/postlund/search-card
Simple Weather Card | Minimalistic weather card for Home Assistant | v0.8.3 | https://github.com/kalkih/simple-weather-card
Slider Button Card | A button card with integrated slider | v1.10.3 | https://github.com/mattieha/slider-button-card
State Switch | 🔹Dynamically replace lovelace cards depending on occasion | 1.9.3 | https://github.com/thomasloven/lovelace-state-switch
Swipe Card | Card that allows you to swipe throught multiple cards for Home Assistant Lovelace | v4.0.0 | https://github.com/bramkragten/swipe-card
Thermostat Popup Card | Lovelace card to use as custom pop-up for thermostat in homekit style | 0.2.6.1 | https://github.com/DBuit/thermostat-popup-card
Upcoming Media Card | 📺 A card to display upcoming episodes and movies from services like: Plex, Kodi, Radarr, Sonarr, and Trakt. | 0.4.3 | https://github.com/custom-cards/upcoming-media-card
Vertical Stack In Card | 📐 Home Assistant Card: Similar to vertical/horizontal-stack, but removes card borders | v0.4.2 | https://github.com/ofekashery/vertical-stack-in-card

### Addon Repositories
- https://github.com/Apipa169/Assistant-Relay-for-Hassio
- https://github.com/danielwelch/hassio-zigbee2mqtt
- https://github.com/gdrapp/hass-addons
- https://github.com/hassio-addons/repository
- https://github.com/hassio-addons/repository-edge
- https://github.com/lolouk44/hassio-addons
- https://github.com/mdegat01/hassio-addons-edge


***

Generated by the [custom readme integration](https://github.com/custom-components/readme)