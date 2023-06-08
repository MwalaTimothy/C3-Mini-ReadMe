
# ESP32-C3-Mini
## Getting
To get started with the ESP32-C3 Mini Version 2 using the Arduino IDE, you'll need to follow these steps:

Step 1: Set up the Arduino IDE
1. Download and install the latest version of the Arduino IDE from the official Arduino website (https://www.arduino.cc/en/software).
2. Launch the Arduino IDE.

Step 2: Install ESP32-C3 Board Support Package
1. Open the Arduino IDE.
2. Go to "File" > "Preferences."
3. In the "Additional Boards Manager URLs" field, enter the following URL:
   ```
   https://github.com/espressif/arduino-esp32/blob/main/package_esp32c3_dev_index.json
   ```
4. Click "OK" to save the preferences.
5. Go to "Tools" > "Board" > "Boards Manager."
6. In the "Boards Manager" window, search for "ESP32" in the search bar.
7. Look for "esp32c3" in the search results and click the "Install" button to install the ESP32-C3 board support package.

Step 3: Select the ESP32-C3 Board
1. Go to "Tools" > "Board" > "ESP32C3 Dev Module."
2. Set the following parameters in the "Tools" menu:
   - Board: "ESP32C3 Dev Module"
   - Flash Frequency: "40 MHz"
   - Flash Mode: "QIO"
   - Flash Size: "4MB (32Mb)"
   - Upload Speed: "115200"
   - CPU Frequency: "80 MHz"
   - Debug Level: "None"

Step 4: Connect the ESP32-C3 Mini Version 2 to your computer
1. Connect your ESP32-C3 Mini Version 2 board to your computer using a USB cable.

Step 5: Upload a Sample Sketch
1. Open one of the example sketches provided by the Arduino IDE to test your setup. You can find examples under "File" > "Examples" > "ESP32C3."
2. Select an example sketch, such as "Blink," which blinks an LED on the board.
3. Click the "Upload" button to compile and upload the sketch to your ESP32-C3 Mini Version 2.

Step 6: Verify the Upload
1. After the upload is complete, the Arduino IDE will display the upload status.
2. If the upload is successful, the LED on the ESP32-C3 Mini Version 2 should start blinking according to the sketch you uploaded.

Congratulations! You have successfully set up the ESP32-C3 Mini Version 2 with the Arduino IDE and uploaded a sample sketch. You can now start exploring and developing your own projects using the ESP32-C3 development board.
