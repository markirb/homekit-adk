# Apple HomeKit ADK for Mongoose OS

This is a port of the official [Apple HomeKit ADK](https://github.com/Apple/HomeKitADK/) to Mongoose OS.

Targeted platforms are ESP8266 and ESP32 for now.

BLE transport is supported as long as BT functionality is present (app includes the `bt-common` lib).

# Examples

A simple Mongoose OS app that uses this library can be found [here](https://github.com/mongoose-os-apps/example-homekit).

A larger project using this library can be found [here](https://github.com/mongoose-os-apps/shelly-homekit).

# TODO

 - MFi chip support
