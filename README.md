# LoRa-Blynk-BRX-Smart-Bases
Smart bases for the brx using long range (LoRa) modules for communication and scoring


This set up makes use of Device to device long range radio transmissions

Using an ESP32 paired to a BLE enabled mobile device or tablet. The device will send BLE commands to the Esp32 that has a Lora module connected
Via serial (rylr896) that will allow for communication over great distances without the need of a a WiFi Network.

Each smart base will be controlled by receiving Lora transmissions from the esp32/Lora module.

Each smart base will also transmit data to the esp32 controller to relay scoring data.
