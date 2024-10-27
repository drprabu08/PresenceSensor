**Mmwave Presence Sensor for Home Assistant & ESP Home, LD2410**
1. Connect the Sensor to the computer using a good micro usb cable that supports data transmission
2. Goto https://web.esphome.io/ and click connect (Install the necessary drivers if the device is not recognised)
3. Install the basic version of esphome by clicking "Prepare for First Use" (Note: Remove the Wemos D1 Mini from the board and install or you'll face cennection issues)
4. A Empty configuration is created in your ESPHome dashboard
5. Edit the Configuration and copy,paste the provided yml file content into your config
6. Update the API Key and set any unique value (Get unique key from: https://esphome.io/components/api.html)
7. Set wifi_ssid and wifi_password in your esphome's secrets.yaml
8. Install the new config
9. Home Assistant should be configured with esphome and it will automatically detects the sensor
