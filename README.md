# ESP32 Weather Display

ESP32_Weather_Display is a project that utilizes the OpenWeatherMap API to retrieve weather information. The OpenWeatherMap API offers a free plan and provides extensive weather data for locations worldwide.

## Requirements

1. **OpenWeatherMap API Key:**
   - Obtain an API key from [OpenWeatherMap](https://home.openweathermap.org/users/sign_up).
   
2. **Latitude and Longitude:**
   - Get the latitude and longitude coordinates for your location. You can find them on Google Maps by right-clicking the location and copying the coordinates. The first number is the latitude, and the second number is the longitude.
     - Example for Egypt:
       - Latitude: 26.837726148229244
       - Longitude: 30.225196562147406

3. **Edit the Code:**
   - Open the Arduino code and provide your WiFi SSID and password in the appropriate fields.

## Getting Started

Follow these steps to set up the ESP32 Weather Display project:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/h0tak88r/ESP32_Weather_Display.git
   ```

2. **Open the Arduino Code:**
   - Open the Arduino IDE.
   - Load the ESP32_Weather_Display code.

3. **Configure the Code:**
   - Replace `<your_wifi_ssid>` and `<your_wifi_password>` with your WiFi credentials.
   - Replace `<your_api_key>`, `<your_lat>`, and `<your_lon>` with the OpenWeatherMap API key, latitude, and longitude.

4. **Upload the Code to ESP32:**
   - Connect your ESP32 board to your computer.
   - Select the appropriate board in the Arduino IDE (e.g., NodeMCU-32S).
   - Upload the code to your ESP32.

5. **Monitor Serial Output:**
   - Open the Serial Monitor in the Arduino IDE to view weather data.

6. **Enjoy Weather Information:**
   - The LCD will display information about the current weather, including description, temperature, and humidity.

## Notes

- Ensure you have a stable internet connection for the ESP32 to fetch weather data.
- The code includes a delay of 60 seconds between updates. Adjust it as needed.

Feel free to contribute, report issues, or suggest improvements. Happy coding!
