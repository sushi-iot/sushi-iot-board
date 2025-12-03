# <u>**ESP32DevKitC-WROVER module**</u>
![ESP32DEVKITC-WROVER](img/ESP32DevKitC-WROVER.png)  

**Description**  
The ESP32 DevKitC board is one of the official Espressif (ESP32 chip producer) dev board, it's available with different SoC models.   
Modules with ESP32-WROVER SoC has an extra 4/8 MB PSRAM.

ℹ️ On [Sushi Board](https://sushi-iot.github.io/sushi-iot-board/) any ESP32 DevKitC v4 board can be used, as they are all pin-compatible.   

⚠️ With [Sushi-IoT-Framework](https://sushi-iot.github.io/sushi-iot-framework/) it's necessary use ESP32-WROVER SoC since it has the extra RAM extension that is required by the framework.

⚠️ If using a model with an external antenna connector, even if it has a visible PCB antenna, it may not be internally connected—so in that case, **you MUST use the external antenna** for proper WiFi operation.

**DOC & Pinout**: [Official Espressif ESP32DevKitC board documentation](https://docs.espressif.com/projects/esp-dev-kits/en/latest/esp32/esp32-devkitc/user_guide.html)

![ESP32DEVKITC-WROVER](img/esp32_devkitC_v4_pinlayout.png)  

**Software control**  
The ESP32 board can be programmed with several IDEs/languages, such as Espressif IDF (C/C++), Arduino (C/C++), and MicroPython.  

ℹ️ [Sushi-IoT-Framework](https://sushi-iot.github.io/sushi-iot-framework/) integrates MicroPython REPL interface, with an extension to manage the [Sushi Board](https://sushi-iot.github.io/sushi-iot-board/) components and to perform some common software tasks that would be a lot more complex to be developed "from 0" with base MicroPython interface.


**Sourcing**    
Some source examples:
* [Espressif shop on Aliexpress](https://it.aliexpress.com/item/1005004441541467.html)
* [Digikey USA](https://www.digikey.com/en/products/detail/espressif-systems/esp32-devkitc-ve/12091812)
* [Mouser EU](https://eu.mouser.com/ProductDetail/Espressif-Systems/ESP32-DevKitC-VE?qs=vmHwEFxEFR%252BnPxzX%2FBK62A%3D%3D)
* [LCSC](https://www.lcsc.com/product-detail/C20437001.html)
* [Google] : search "esp32devkitc-ve" or "esp32devkitc-wrover".

Note: The official ESP32DevKitC module coding define board with WROVER as "VE" (PCB antenna) or "VIE" (external antenna).