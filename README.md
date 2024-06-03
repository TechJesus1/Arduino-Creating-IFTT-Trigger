# Light Sensor IoT Project

This project utilizes a BH1750 light sensor connected to an Arduino board to detect sunlight levels. When the sunlight level surpasses a certain threshold, it triggers an IFTTT webhook to notify external services.

## Components Used

- BH1750 Light Sensor
- Arduino Board
- WiFi Module (e.g., WiFiNINA)

## Dependencies

- BH1750 library (`BH1750.h`)
- Wire library (`Wire.h`)
- WiFiNINA library (`WiFiNINA.h`)

## Setup Instructions

1. Connect the BH1750 light sensor to the Arduino board.
2. Connect the Arduino board to a WiFi network.
3. Update the WiFi SSID, password, and IFTTT webhook key in the code.
4. Upload the code to the Arduino board.

## Operation

The Arduino board continuously reads the light level from the BH1750 sensor. If the light level exceeds a certain threshold, it triggers a webhook to an IFTTT service, indicating sunlight detection.

