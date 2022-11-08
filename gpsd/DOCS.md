# Home Assistant GPSD Add-on: GPSD

## How to use

Plug a [compatible GNSS device](https://gpsd.gitlab.io/gpsd/hardware.html) into a serial port or USB serial adapter.

Configure the correct serial device and in the configuration section.

This Add-on replaces the local installation requirements listed at in the [GPSD  integration](https://www.home-assistant.io/integrations/gpsd/) for supervised installations.

Add the following to your configuration.yaml after installing this addon to get GPS data flowing into your Home Assistant.

```
# Example configuration.yaml entry
sensor:
  - platform: gpsd
```

More information from, and many thanks to, the [GPSD](https://gpsd.gitlab.io/gpsd/) team!
