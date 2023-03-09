# Simple MQTT for ESP32

This is a simple MQTT client for ESP32. It is based on the [ESP32 MQTT library](https://github.com/knolleary/pubsubclient).

## Installation

We are using PlatformIO to build and upload the code to the ESP32. You can install PlatformIO by following the instructions on their [website](https://platformio.org/).

## Configuration

The configuration is done in the `src/config.h` file. You need to set the following parameters:

- `WIFI_SSID`: The SSID of the WiFi network to connect to.
- `WIFI_PASSWORD`: The password of the WiFi network to connect to.
- `MQTT_SERVER`: The IP address of the MQTT server.
- `MQTT_PORT`: The port of the MQTT server.
- `MQTT_USERNAME`: The username to use to connect to the MQTT server.
- `MQTT_PASSWORD`: The password to use to connect to the MQTT server.
- `MQTT_TOPIC`: The topic to subscribe to.

## Building and uploading

To build and upload the code to the ESP32, run the following command:

```bash
pio run --target upload
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [ESP32 MQTT library](https://github.com/knolleary/pubsubclient)
- [EMQX](https://www.emqx.io/)
- [EMQX Arduino Code](https://github.com/emqx/MQTT-Client-Examples/tree/master/mqtt-client-ESP32) (You can find the license in the `mqtt-client-ESP32` folder.)
- [PlatformIO](https://platformio.org/)
