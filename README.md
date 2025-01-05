# ESP32 IP Cam
ESP32 IP Camera


# Features
This is just my checklist
- [ ] Take picture and save 1 frame in PSRAM
- [ ] OTA update
- [ ] Save picture to SD card
- [ ] Configure WiFi using the ESP32 itself as an AP
- [ ] Automate testing
- [ ] HTTP API endpoints

# Getting started
1. Install idf https://github.com/espressif/esp-idf

1. Activate idf environment
    ``` bash
    . ~/git/esp-idf/export.sh
    ```

1. Build
    ``` bash
    idf.py build
    ```

1. Upload
    ``` bash
    idf.py flash
    ```

# Some tricks
- If things go wrong
    ```bash
    idf.py fullclean
    ```

- Run tests
    ``` bash
    pytest src/pytest*.py
    ```

- Monitor
    ``` bash
    idf.py monitor
    ```

# Reference
- WiFi Manager feature is inspired by: https://github.com/martin-ger/esp32_nat_router
