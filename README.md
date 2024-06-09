## WiFi-Controlled 8-Relay Automation System with NodeMCU

### Overview

This project involves creating a smart home automation system using a NodeMCU to control 8 relays over WiFi. The system uses the Blynk platform for remote control and monitoring, making it ideal for automating various household devices.

### Components

- NodeMCU (ESP8266)
- 8-Channel Relay Module
- PIR Sensor
- Power Supply
- WiFi Connection
- Blynk App

### Installation

1. **Clone or Download the Repository:**
   ```bash
   git clone https://github.com/yourusername/yourrepository.git
   ```

2. **Install Required Libraries:**
   - ESP8266WiFi
   - BlynkSimpleEsp8266

### Configuration

1. **Update the Blynk Auth Token:**
   Replace the placeholder auth token in the code with your Blynk Auth Token.

2. **Set WiFi Credentials:**
   Replace the placeholder SSID and password in the code with your WiFi network's SSID and password.

### Wiring

- Connect the relay module to the NodeMCU digital pins (D1 to D8).
- Connect the PIR sensor to pin D5 (or any other available pin).

### Usage

1. **Upload the code to your NodeMCU.**
2. **Open the Blynk app and create a project.**
3. **Add a widget for the virtual pin V0 to monitor the PIR sensor.**
4. **Connect the NodeMCU to your WiFi network.**
5. **Control the relays and monitor the PIR sensor status via the Blynk app.**

### Notes

- Make sure to replace the placeholder credentials and Blynk Auth Token with your actual information.
- Modify the initial state settings for the relays to match your desired configuration.
- Extend the pinMode and digitalWrite statements if using more relays.

### License

This project is licensed under the MIT License.

### Acknowledgements

- Thanks to the Blynk community for their support and documentation.
- Special thanks to [Your Name/Username] for the project idea and implementation.

### Troubleshooting

- Ensure the NodeMCU is properly connected to your WiFi network.
- Verify all connections to the relay module and PIR sensor.
- Check the serial monitor for debugging information.

---

Feel free to customize this README file to better match your project specifics and personal style!
