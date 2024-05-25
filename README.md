# WiFi F#cker
![ESP8286](https://github.com/Adrilaw/WiFi-Fucker/assets/65346144/e54dc17e-f9e4-495c-a609-b26146d23050)


WiFi F#cker is a cutting-edge tool crafted specifically tailored for use with the ESP8266 module. This versatile tool empowers users to execute sophisticated WiFi attacks, including Evil Twin and Deauthentication attacks, for advanced network security testing.

## Features

- **Evil Twin Attack**: Create a deceptive rogue access point to intercept network traffic and extract sensitive data discreetly.
- **Deauthentication Attack**: Forcefully disconnect clients from a target network, compelling them to reconnect and potentially exposing their credentials.
- **ESP8266 Compatibility**: WiFi F#cker is intricately designed to seamlessly integrate with the ESP8266 module, ensuring optimal performance and flexibility for WiFi penetration testing.

## Disclaimer

WiFi F#cker is an educational tool intended for legitimate security testing purposes only. Any unauthorized or malicious use of this tool is strictly prohibited and may violate legal regulations. The developers and maintainers of WiFi F#cker disclaim any responsibility for misuse of this tool.

## Setup

To unleash the full potential of WiFi F#cker, follow these steps to set up the ESP8266 module in Arduino:
1. Install Arduino IDE
2. In Arduino go to File -> Preferences add this URL to Additional Boards Manager URLs -> https://raw.githubusercontent.com/SpacehuhnTech/arduino/main/package_spacehuhn_index.json
3. In Arduino go to Tools -> Board -> Boards Manager search for and install the deauther package
4. Download and open WiFi F#cker.ino with Arduino IDE
5. Select an ESP8266 Deauther board in Arduino under tools -> board
6. Connect your device and select the serial port in Arduino under tools -> port
7. Click Upload button

Note: Ensure your ESP8266 module has a minimum of 4MB flash memory for optimal performance.

## Usage

To effectively utilize WiFi F#cker and explore its capabilities, connect to the "WiFi F#cker" network and use the password "FuckWiFi" and leverage the command line interface with the following commands:

## License

WiFi F#cker is licensed under the [MIT License](LICENSE) to promote open collaboration and innovation in the realm of network security testing.
