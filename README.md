# Temperature Monitor Project

This project monitors and logs temperature data using an ESP8266 microcontroller and a thermistor. The temperature data is displayed on an LCD screen and periodically sent to a remote server via HTTP POST requests.

## Components
- ESP8266
- Thermistor
- LCD (I2C)
- Resistors
- Breadboard and wires

## Features
- Real-time temperature monitoring
- LCD display for current temperature
- Periodic data logging to a remote server
- WiFi connectivity

## Installation
### Hardware Setup
1. Connect the thermistor to the analog input of the ESP8266.
2. Connect the LCD to the I2C pins of the ESP8266.
3. Power the ESP8266 using a suitable power source.

### Software Setup
1. Clone this repository:
    ```sh
    git clone https://github.com/yourusername/TemperatureMonitorProject.git
    ```
2. Open the project in the Arduino IDE.
3. Install the required libraries:
    - ESP8266WiFi
    - ESP8266HTTPClient
    - LiquidCrystal_I2C
4. Configure your WiFi SSID and password in the code:
    ```cpp
    const char* ssid = "yourSSID";
    const char* password = "yourPASSWORD";
    ```
5. Upload the code to your ESP8266.

## Usage
1. Connect the components as described in the circuit diagram (coming soon).
2. Power up the ESP8266.
3. The LCD screen will display the current temperature.
4. The temperature data will be sent to the server every 15 minutes.

## Circuit Diagram
(Insert a detailed circuit diagram here)

## Troubleshooting
- If the LCD does not display anything, check the I2C connections and the I2C address.
- If the temperature data is not being sent to the server, check the WiFi connection and the server URL.

## Contributing
1. Fork the repository.
2. Create a new branch: `git checkout -b my-feature-branch`.
3. Make your changes and commit them: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin my-feature-branch`.
5. Open a pull request.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements
- Inspiration, code snippets, etc.

## Contact
Created by [vedategunduz](https://github.com/vedategunduz) - feel free to contact me!
