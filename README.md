# Blebox custom component for Home Assistant

## How to load custom components
https://developers.home-assistant.io/docs/en/creating_component_loading.html

## Blebox wLightBox
__To enable this switch, add the following lines to your configuration.yaml file:__
```
switch:
  - platform: blebox_wlightbox
    host: IP_ADDRESS
```
__Configuration variables:__
* __host__ (*Required*): The IP address of your switchBox(D), eg. 192.168.1.32
* __name__ (*Optional*): The name to use when displaying this switch. If not set, will be used the device name

<img src="https://raw.githubusercontent.com/d4m/hassio_components/master/blebox_switchbox.png" />
