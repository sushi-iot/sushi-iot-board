**Sushi Board is an ESP32-based programmable modular embedded system for general-purpose IoT, suitable for STEM education and DIY electronics projects.**

100% based on widely available commercial modules, making it cost-effective and easy to source.



Description
If you enjoy DIY electronics and coding, you've likely experimented with various boards and modules. When it’s time to build something practical and polished, connecting everything cleanly can be a challenge. Sushi Board simplifies this by helping you integrate modules into a neat, functional setup, ideal for IoT projects.

For MAKERs
* A carrier board that connect all the essential components needed to create a complete IoT unit, suitable for various applications, minimizing the complexity of assembling different components and boards without requiring extensive soldering or wiring.
* Only the CPU is mandatory; then you simply plug in the modules you need for your specific purposes.

For students and educational purposes
* Sushi Board offers a modular system that can be shared across multiple projects, from simple setups to more complex, DIY electronics systems. 
* It’s not just for desk experiments; you can build something practical and functional.
* You can choose the level of knowledge that suits you best. An Arduino-style, high-level approach works well for beginners and hobbyists, but if you're interested in programming and aim to become a professional, you'll need to dive deeper into how things work behind the scenes. The Sushi Board documentation gives you the flexibility to decide your learning path.
* A set of step-by-step software examples is provided, not just for basic tasks like ‘blinking a LED,’ but for full-scale, DIY electronics projects, all based on the same core hardware connected to the Sushi Board.
* The plan is to develop a series of educational projects covering various IoT applications, using the same core software-hardware offered by the Sushi."



Advantages
* Based on ESP32 SoC: a reliable choice in the IoT field. You have access to a powerful ecosystem with numerous resources available online.
* 100% based on very common commercial modules widely available online for Arduino and DIY electronics projects. Sushi board just help you connect them all together.
* You can code with your favourite compiler : Arduino, microPython (even without a PC), Scratch, ESP-IDF, etc. 
* Open source hardware: both the CPU module and the Sushi Board come with wiring diagrams provided.
Applications
* Home automation systems
* IoT central units
* Alarm systems
* Domotics servers
* Remote monitoring and data sampling systems (example weather centrals)
* Local and remote devices control (by local user interface, web interface, modem interface)

Hardware features
All the ingredients that are needed for a myriad of applications:
* ESP32-DevKitC V4
* 16x digital GPIN 
* 2x Relay OUT (10A 250V AC)
* 5x digital direct GPIO, 1 x GPO , 2 x GPI (LEDs, extra UART, etc.) 
* Physical keyboard
* OLED Display 
* Connectivity: Wi-Fi, Bluetooth, modem 2G/3G/4G, UART, I2C
* Power supply modes: 5V (USB adapter or wired) ; Battery only ; 5V + backup battery (for when grid power is missing)
* Backup battery
* Power status and battery level acquisition 
* Buzzer for audio alerts
* Temperature sensor
* Size: 90x110 mm (both carrier and TOP boards)


Resources
* Espressif ESP32-DevKitC V4 user guide
* Espressif modules
* Sushi board on Instagram
* MicroPython project



Projects and pictures

Just the base and top (optional) PCBs

unmounted Sushi board carrier (right) and TOP (left) 

Carrier board CAD rendering
SANDWICH configuration
This configuration is useful during development and testing on the desk.


mounted board in sandwich configuration, attached to the PC for programming



The name "Sushi board" comes from the idea that, like sushi—a traditional Japanese specialty—the Sushi board is composed of various ingredients (the modules) that can be added or customized based on your preferences.


Disclaimer

This product is intended for educational, hobbyist, and prototyping purposes only.
It is not a certified end-user product and is not suitable for industrial, commercial, or medical applications.
The manufacturer and distributors assume no responsibility for any damage, injury, or loss resulting from the use, misuse, or improper handling of this product.
This product is provided "as is" without warranty of any kind, either expressed or implied, including but not limited to warranties of merchantability, fitness for a particular purpose, or non-infringement.

This is not a toy and not intended for children under 14 years of age.
It is classified as a development tool / unfinished electronic assembly, not subject to CE or FCC certification as a finished consumer device.
Use at your own risk.
