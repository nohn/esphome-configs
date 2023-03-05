My collection of ESPHome configurations includes the following platforms:

- [MH-Z19 CO_2 Gas Sensor + TM1637 4 Digit 7 Segment Display](/templates/sensors/gas_co2_mhz19_display.yaml) ([Example Device](/example-mhz19-tm1637-co2.yaml))
- [MH-Z19 CO_2 Gas Sensor + Red LED + Green LED](/templates/sensors/gas_co2_mhz19_2led.yaml) ([Example Device](/example-mhz19-2led-co2.yaml)) (deprecated)
- [CAJOE Geiger Counter / Radiation Sensor](/templates/sensors/radiation_cajoe.yaml) ([Example Device](/example-cajoe-radiation.yaml))
- [IKEA Vindriknting Particle Sensor](/templates/sensors/radiation_cajoe.yaml) ([Example Device](/example-vindriktning-particle.yaml))

All [boards](/templates/boards/) are configured to use ESP-IDF instead of Arduino for [Bluetooth proxy](/templates/common/bluetooth_proxy.yaml) performance. Additionally, all devices are configured to expose the [wifi_signal](/templates/sensors/wifi_signal.yaml) sensor.