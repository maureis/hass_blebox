# Blebox custom component for Home Assistant

## How to load custom components
https://developers.home-assistant.io/docs/en/creating_component_loading.html

## Blebox wLightBox RGBW/RGB component
__To enable this switch, add the following lines to your configuration.yaml file:__
```
switch:
  - platform: blebox_wlightbox
    host: IP_ADDRESS
```
__Configuration variables:__
* __host__ (*Required*): The IP address of your switchBox(D), eg. 192.168.1.32
* __name__ (*Optional*): The name to use when displaying this switch. If not set, will be used the device name

## Blebox API

Component was tested on version [0.1.0](https://technical.blebox.eu/wLightBoxAPI/) of Blebox API for wLightBox.