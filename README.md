*DEPRECATED. I've now moved my ESPHome configs to the same repo as my Home Assistant config. See [here](https://github.com/johnboiles/homeassistant-config/tree/master/esphome) for my ESPHome configs.*

# ESPHome Air Sensor

My ESPHome YAML configuration for my MHZ19 CO2 sensor + DHT22 temperature/humidity sensor + PMS5003 particulate sensor.

## First time setup

Install the `esphome` tool

    sudo pip install esphome

Make a `secrets.yaml` with your WiFi credentials

    cp secrets.yaml.example secrets.yaml

## To upload new versions

    esphome air_sensor.yaml run

## To read the logs while running

    esphome air_sensor.yaml logs
