# Embedded FWupdate OTA

This repository provides a comprehensive solution for updating device firmware over the air (OTA).

# Usage
```
git clone https://github.com/ZakariyaaEddaaf/embedded-fwupdate-ota.git
cd embedded-fwupdate-ota
code .
```

Build the project and flash the firmware to the ESP32 device. Once the firmware is flashed, the device will broadcast an open WiFi network with the SSID FWupdateMe. Connect to this network and open http://192.168.4.1 in your web browser.



![App Screenshot](https://github.com/ZakariyaaEddaaf/embedded-fwupdate-ota/blob/main/screenshot/fwupdate_http_basic.png?raw=true)


## License
This project is licensed under the MIT license. See `LICENSE` for details.

