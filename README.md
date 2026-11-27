# Awesome-IOT-Hardware-Smartphone-Bridging

# Awesome-IOT-Hardware-Smartphone-Bridging

Top IOT Hardware Smartphone Bridging (Opensource) 🌟 Star if you like it! 🌟

A curated list of top IoT hardware and smartphone bridging platforms, mobile-to-microcontroller dashboards, BLE/Wi-Fi telemetry bridges, smart home automation hubs, and MQTT device orchestration tools—featuring commercial SaaS/Hosted platforms alongside their open-source equivalents.

---

## Table of Contents

- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source Equivalents & Tools](#open-source-equivalents--tools)
  - [ESP32 & Smartphone Direct Bridging Frameworks](#esp32--smartphone-direct-bridging-frameworks)
  - [Self-Hosted IoT Dashboards & Device Management Platforms](#self-hosted-iot-dashboards--device-management-platforms)
  - [Smart Home & Mobile App Orchestration Hubs](#smart-home--mobile-app-orchestration-hubs)
  - [Custom Microcontroller Firmware & No-Code IoT Builders](#custom-microcontroller-firmware--no-code-iot-builders)
  - [High-Throughput MQTT Brokers & Telemetry Bridges](#high-throughput-mqtt-brokers--telemetry-bridges)
- [Contributing](#contributing)

---

## SaaS/Hosted Platforms

Commercial, cloud-hosted IoT device management suites, drag-and-drop mobile IoT dashboard apps, and enterprise cloud device brokers.

* **[Blynk IoT](https://blynk.io)** - Commercial low-code IoT platform offering native iOS/Android mobile apps, cloud dashboards, and OTA firmware updates for ESP32, Arduino, and Raspberry Pi.
* **[Arduino Cloud](https://arduino.cc)** - Official cloud platform by Arduino enabling real-time sensor dashboards, smartphone remote control apps, and over-the-air sketch uploads.
* **[Adafruit IO](https://adafruit.com)** - Hosted cloud data service and dashboard builder designed for makers to connect microcontrollers and mobile interfaces over MQTT/REST.
* **[Particle Cloud](https://particle.io)** - Integrated edge-to-cloud IoT platform providing cellular/Wi-Fi fleet management, mobile SDKs, and secure device provisioning.
* **[ThingsBoard Cloud](https://thingsboard.cloud)** - Fully managed SaaS version of ThingsBoard offering multi-tenant telemetry visualization, rule engines, and mobile IoT applications.
* **[Ubidots](https://ubidots.com)** - Commercial IoT application enablement platform for building white-label web and mobile sensor dashboards without backend coding.
* **[Datacake](https://datacake.co)** - Low-code cloud IoT platform supporting LoRaWAN, MQTT, and cellular devices with instant mobile-responsive dashboards.
* **[Losant](https://losant.com)** - Enterprise cloud IoT platform featuring visual workflow engines, edge compute agents, and end-user mobile/web experiences.
* **[Tuya Developer Platform](https://tuya.com)** - Commercial PaaS ecosystem providing cloud connectivity, white-label smartphone apps, and smart hardware modules.
* **[AWS IoT Core](https://amazon.com)** - Managed enterprise cloud service connecting billions of IoT devices to AWS cloud applications and mobile backends via MQTT and HTTPS.

---

## Open-Source Equivalents & Tools

Free and open-source software (FOSS) smartphone-to-hardware bridges, self-hosted IoT dashboards, local smart-home mobile hubs, microcontroller firmwares, and MQTT brokers.

### ESP32 & Smartphone Direct Bridging Frameworks

* **[esp32-iphone-agent (onehumanbeing)](https://github.com)** - Open-source project bridging ESP32 hardware directly with iPhone capabilities for seamless mobile-to-microcontroller interaction.
* **[ESP-DASH](https://github.com)** - Blazingly fast, open-source C++ library creating real-time, responsive smartphone and web dashboards hosted directly on ESP8266/ESP32 microcontrollers.
* **[RemoteXY (Open Libraries & Local Web/BLE Bridges)](https://github.com)** - Hardware communication libraries enabling direct smartphone GUI control over Bluetooth, BLE, Wi-Fi, and Ethernet.
* **[Dabble (STEMpedia)](https://github.com)** - Open-source Arduino/ESP32 library transforming a smartphone into a virtual I/O shield (gamepad, accelerometer, GPS, camera, terminal) over BLE.
* **[Blynk Library (Open-Source Device C++ SDK)](https://github.com)** - Open-source C++ microcontroller client library supporting ESP32, Arduino, and Linux boards.
* **[Bluepad32](https://github.com)** - Open-source firmware turning ESP32 boards into universal Bluetooth hosts capable of bridging phones, gamepads, and HID devices to hardware.

### Self-Hosted IoT Dashboards & Device Management Platforms

* **[ThingsBoard (Community Edition)](https://github.com)** - Leading open-source IoT platform for data collection, processing, visualization, and device management with open-source Flutter mobile apps.
* **[ThingSpeak (Open-Source Server)](https://github.com)** - Open-source IoT analytics and MATLAB/charting server application for aggregating and visualizing live sensor streams.
* **[Thinger.io (Open-Source Core)](https://github.com)** - Open-source hardware libraries and cloud/self-hosted IoT infrastructure for bidirectional device control and mobile dashboards.
* **[Mainflux / Magistrala](https://github.com)** - Modern, scalable, open-source IoT cloud platform written in Go supporting MQTT, CoAP, HTTP, WebSockets, and multi-tenant device twins.
* **[Kaa IoT (Open-Source Components) / DeviceHive](https://github.com)** - Open-source IoT data platform providing REST/WebSocket/MQTT APIs to connect smart hardware with mobile and analytics apps.
* **[Node-RED](https://github.com)** - Flow-based open-source programming tool wiring together hardware devices, APIs, MQTT, and responsive mobile dashboards (Node-RED Dashboard 2.0).

### Smart Home & Mobile App Orchestration Hubs

* **[Home Assistant](https://github.com)** - The premier open-source home automation platform featuring official open-source iOS/Android companion apps that bridge phone sensors and notifications directly to IoT hardware.
* **[openHAB](https://github.com)** - Vendor- and technology-agnostic open-source automation software with native mobile apps for unified hardware control.
* **[Domoticz](https://github.com)** - Lightweight open-source home automation system written in C++ supporting custom sensors, switches, and mobile remote control.
* **[ioBroker](https://github.com)** - Open-source integration platform connecting hundreds of IoT protocols (Zigbee, Z-Wave, MQTT, BLE) to custom mobile visualization interfaces.

### Custom Microcontroller Firmware & No-Code IoT Builders

* **[ESPHome](https://github.com)** - Open-source system to control ESP8266/ESP32 and RP2040 boards via simple YAML configuration files with seamless smartphone and Home Assistant integration.
* **[Tasmota](https://github.com)** - Alternative open-source firmware for ESP8266/ESP32 devices freeing smart hardware from proprietary vendor clouds (like Tuya) with local WebUI and MQTT.
* **[OpenBeken (OpenBK7231T_App)](https://github.com)** - Open-source Tasmota-compatible firmware replacement for non-ESP Wi-Fi modules (BK7231, BL602, W800) found in commercial Tuya smart devices.
* **[MicroPython](https://github.com)** - Lean, efficient open-source Python 3 implementation for microcontrollers enabling rapid BLE and Wi-Fi smartphone bridging scripts.

### High-Throughput MQTT Brokers & Telemetry Bridges

* **[Eclipse Mosquitto](https://github.com)** - Lightweight, industry-standard open-source MQTT message broker ideal for bridging smartphones and low-power IoT devices.
* **[EMQX](https://github.com)** - Highly scalable, distributed open-source MQTT broker capable of handling millions of concurrent IoT and mobile client connections.
* **[NanoMQ](https://github.com)** - Ultra-lightweight, blazingly fast open-source MQTT broker written in pure C engineered for IoT edge gateways and embedded hardware.
* **[OwnTracks](https://github.com)** - Open-source mobile location and telemetry bridging ecosystem using MQTT/HTTP to stream smartphone GPS and sensor events to self-hosted servers.

---

## Contributing

Contributions are welcome! Feel free to open a Pull Request to add more open-source IoT platforms, smartphone-to-ESP32 bridges, self-hosted dashboards, or open microcontroller firmwares.

1. Fork the repository.
2. Add your project under the appropriate category with a concise description.
3. Submit a Pull Request.
