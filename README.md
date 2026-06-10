# CANipulator Documentation

The **CANipulator** is a versatile CAN bus interface designed for bridging, translating, baud-rate matching, and manipulating traffic between two CAN networks. Designed for automotive environments, it is equally suited to industrial, marine, and other CAN-based applications.

### CANipulator V1 features
- 160 MHz ESP32-C6-WROOM-1U (U.FL) with 8 MB Flash
- Automotive-qualified 4–18 V power input with fuse, reverse-polarity protection, and transient suppression up to 40 V
- Dual CAN bus transceivers supporting up to 1 Mbps
- Silent mode and Shutdown mode support
- ESD-protected CAN interfaces
- Solderable termination resistor jumpers
- Reset and Boot buttons (Boot button may be repurposed as a user button after startup)
- Two Molex DuraClik connectors (V+, GND, CAN-H, CAN-L)
- 10-pin female expansion header (3.3 V, GND, and 8 GPIOs)
- USB Type-C connector for power, programming, and debugging

### CANipulator V2 features
- 240 MHz ESP32-C5-WROOM-1U (U.FL) with 8 MB Flash and 8 MB PSRAM (subject to availability)
- Automotive-qualified 4–18 V power input with fuse, reverse-polarity protection, and transient suppression up to 40 V
- Dual CAN bus transceivers supporting up to 1 Mbps, with optional CAN-FD support up to 5 Mbps
- Silent mode and Shutdown mode support
- ESD-protected CAN interfaces
- Jumper-selectable termination resistors for quick installation and testing
- Reset and Boot buttons (Boot button may be repurposed as a user button after startup)
- Two Molex DuraClik connectors (V+, GND, CAN-H, CAN-L)
- 10-pin female expansion header (3.3 V, GND, and 8 GPIOs)
- USB Type-C connector for power, programming, and debugging
- Optional microSD card slot

https://www.tindie.com/products/fusion/canipulator-automotive-dual-can-esp32-interface/

## To get started in Arduino IDE
* Make sure your [arduino-esp32](https://github.com/espressif/arduino-esp32/) library (IDF 5.5+) and Arduino IDE is up to date
* Download/clone https://github.com/TechOverflow/esp32_can (includes CANipulator examples)
* Download/clone https://github.com/collin80/can_common (required for esp32_can)
* Download/clone https://github.com/TechOverflow/SmartLeds (required in CANipulator examples)
* Download/clone https://github.com/Beirdo/Arduino-PCA9536 (CANipulator V2 only)
* In board selection choose **ESP32C6 Dev Module** (CANipulator V1) or **ESP32C5 Dev Module** (CANipulator V2)
* Select the COM port of the connected device
* Load an example and upload
