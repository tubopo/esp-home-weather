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
