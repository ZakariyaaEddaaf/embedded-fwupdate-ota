# Embedded FWupdate OTA

This repository provides a comprehensive solution for updating device firmware over the air (OTA).

# Usage
```
git clone https://github.com/ZakariyaaEddaaf/embedded-fwupdate-ota.git
cd embedded-fwupdate-ota
code .
```

Build the project and flash the firmware to the ESP32 device. Once the firmware is flashed, the device will broadcast an open WiFi network with the SSID FWupdateMe. Connect to this network and open http://192.168.4.1 in your web browser.

Once you have connected to the network and entered the IP address in your browser, the firmware update webpage will appear.

![App Screenshot](https://github.com/ZakariyaaEddaaf/embedded-fwupdate-ota/blob/main/screenshot/fwupdate_http_basic.png?raw=true)

Click "Browse" to select the new firmware from your local computer, then click the "Upload" button to update the firmware.

![App Screenshot](https://github.com/ZakariyaaEddaaf/embedded-fwupdate-ota/blob/main/screenshot/fwupdate_http_update.png?raw=true)


## License
This project is licensed under the MIT license. See `LICENSE` for details.

