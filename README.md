# other_releases

**Firmware for ESP microcontrollers and sundry material**

---

## Module: ESP01-S (1 MB flash)

- **espat_176_esp01s.zip** : Contains `espat_176_esp01s.bin`, ESP-AT (version 1.7.6) binary based on the *legacy* ESP8266 NonOS SDK.

      AT+GMR
      AT version:1.7.6.0(Jan 24 2022 08:56:02)
      SDK version:3.0.6-dev(072755c)
      compile time:Jun 17 2024 07:38:00
      Bin version(Wroom 02):1.7.6


- **espat_221_esp01s.zip** : Contains `espat_221_esp01s.bin`, ESP-AT (version 2.2.1) binary based on the ESP8266 RTOS SDK.

      AT version:2.2.2.0-dev(e3958a6 - ESP8266 - Oct 30 2024 02:42:04)
      SDK version:v3.4-84-ge19ff9af
      compile time(f37fbc77):Nov  5 2024 15:58:02
      Bin version:2.2.1(ESP8266_1MB)
      AT version:2.2.2.0-dev(e3958a6 - ESP8266 - Oct 30 2024 02:42:04)

  > Since Nov 5, 2024 there have been more commits to the [release/v2.2.0.0](https://github.com/espressif/esp-at/tree/release/v2.2.0.0_esp8266) branch of ESP-AT.

See [Installing the AT Firmware on an ESP-01S](https://sigmdel.ca/michel/ha/esp8266/ESP01_AT_Firmware_en.html) for details.


--- 

## Module: ESP32-2432S028R (Cheap Yellow Display)

- **cydMacroPad.zip** : Contains `cydMacroPad.bin` macro keypad firmware for the ESP32-2432S028R (aka CYD - [Cheap Yellow Display](https://github.com/witnessmenow/)) development board. See [cydMacroPad/README.md](https://github.com/sigmdel/lazmacropad/blob/main/cydMacroPad/README.md) and [TFT_eTouch](https://github.com/sigmdel/TFT_eTouch/blob/master/README_TOO.md).


---

## Scripts, Icons and Configuration Files for Globe 2-Socket Outdoor Plug (50151) with bk7231T microcontroller

- **bk7231T-GlobeOutdoor-Plug.zip** : Contains an `autoexec.bat` file to setup event handlers in the OpenBK7231T_App, two Domoticz custom icon files, a Domoticz On/Off Action bash script, and a json template for a simplified device configuration. See [A Beken BK7231T Device In Domoticz](https://sigmdel.ca/michel/ha/domoticz/beken7231_domoticz_en.html).
