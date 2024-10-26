# other_releases

**Firmware for microcontrollers.**

- **espat_esp01_2024_10_25.zip** : Contains `factory_ESP8266_1MB.bin`, ESP-AT V2.2.1 binary for ESP8266 with 1MB flash memory obtained by compiling the `esp-at` source code in [GitHub Codespaces](https://github.com/features/codespaces). See [Compile AT Firmware for ESP-01S](https://github.com/bablokb/circuitpython-esp32at/blob/main/doc/at_firmware_compile_esp01s.md) by bablokb which *contains simple to use instructions for compiling your own firmware. You need nothing except a Github-account and about a quarter of an hour*.

  <blockquote>

    AT+GMR  
    AT version:2.2.2.0-dev(b65f53f - ESP8266 - Jul  5 2024 06:59:26)  
    SDK version:v3.4-84-ge19ff9af  
    compile time(73094a40):Oct 25 2024 03:20:06  
    Bin version:2.2.1(ESP8266_1MB)  
  </blockquote>

- **espat_esp01.zip** : Contains `espat_esp01.bin`, ESP-AT V2.2.1 binary for ESP8266 with 1MB flash memory (factory_ESP8266_1MB.bin in esp8285-1MB-at.zip) patched with `at.py` to run on the ESP-01S module. See [Installing the AT Firmware on an ESP-01S](https://sigmdel.ca/michel/ha/esp8266/ESP01_AT_Firmware_en.html) for details.

  <blockquote>
  
    AT+GMR  
    AT version:2.2.2.0-dev(952f658 - ESP8266 - Nov 23 2022 06:37:28)  
    SDK version:v3.4-67-g82d8ba2c  
    compile time(38991f7):Jul 21 2023 04:07:04  
    Bin version:2.2.1(ESP8266_1MB)  
  </blockquote>


- **cydMacroPad.zip** : Contains `cydMacroPad.bin` macro keypad firmware for the ESP32-2432S028R (aka CYD - [Cheap Yellow Display](https://github.com/witnessmenow/)) development board. See [cydMacroPad/README.md](https://github.com/sigmdel/lazmacropad/blob/main/cydMacroPad/README.md) and [TFT_eTouch](https://github.com/sigmdel/TFT_eTouch/blob/master/README_TOO.md).
