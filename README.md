# CANipulator Documentation

The **CANipulator** is a CAN bus interface that allows the bridging, translation, baud-matching, or manipulation of traffic on two CAN networks between nodes. It was designed with automotive environments in mind, but can also be used in other CAN systems. At the heart is a 160 MHz ESP32-C6, which offers not only dual TWAI (Two-Wire Automotive Interface) controllers, but also 802.11b/g/n/ax WiFi, BLE 5.3, native USB, and many other features.

https://www.tindie.com/products/fusion/canipulator-automotive-dual-can-esp32-interface/

## To get started in Arduino IDE
* Make sure your [arduino-esp32](https://github.com/espressif/arduino-esp32/) library (IDF 5.5+) and Arduino IDE is up to date
* Download/clone https://github.com/TechOverflow/esp32_can (includes CANipulator examples)
* Download/clone https://github.com/collin80/can_common (required for esp32_can)
* Download/clone https://github.com/TechOverflow/SmartLeds (required in CANipulator examples)
* In board selection choose **ESP32C6 Dev Module** (CANipulator) or **ESP32C5 Dev Module** (CANipulator V2)
* Select the COM port of the connected device
* Load an example and upload
