# esp-home-weather 🌡️

 The system is designed to measure temperature, humidity, and atmospheric pressure, providing real-time data that can be used for various applications such as weather forecasting, environmental monitoring, and home automation.

## Features

+ Real-time temperature, humidity, and pressure monitoring
+ Easy integration with home automation systems
+ Low power consumption
+ Wireless data transmission

## Hardware

+ esp8266 Wemos D1 Mini Pro
+ Bosch BME280 sensor

## Install

```bash
esphome run weather.yaml
```

## Log

```bash
esphome logs --topic weather/log weather.yaml
```

### Status LED

Blink slowly (about every second) when a warning is active. Warnings are active when for example reading a sensor value fails temporarily, the WiFi/MQTT connections are disrupted, or if the native API component is included but no client is connected.

Blink quickly (multiple times per second) when an error is active. Errors indicate that ESPHome has found an error while setting up. In most cases, ESPHome will still try to recover from the error and continue with all other operations.

Stay off otherwise.
