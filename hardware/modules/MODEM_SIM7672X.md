# <u>**SIM7672X (NA,E,G)**</u>
<img src="img/SIM7672G.png" width="50%" >  

**Description**  
The SIMcom SIM7672X (X=NA,E,G) is a modem module with worldwide band support (NA=North America, E=Europe, G=Global) and certifications.
The board in the picure is just one of the ones that mounts this module and it's just an example.
ℹ️ The board model in the picture (one of the more common in the market) was successfully tested with [Sushi Board](https://sushi-iot.github.io/sushi-iot-board/) & [Sushi Framework](https://sushi-iot.github.io/sushi-iot-framework/). The arrow indicate where the 4G antenna must be connected.  

**DOC**: [Simcom SIM7672X](https://en.simcom.com/product/SIM7672.html)



**Pinout**
Typical pins used to control the modem are:
* PK : Modem "power key" pin (if required by the module)
* GND 
* TX : Modem UART TX (micro RX)
* RX : Modem UART RX (micro TX)
* VCC : 5V power supply for modem (the accepted range depend on the specific board)

**Software control**
With AT commands by the UART interface.

**Sourcing**  
* [Google] : search "SIM7672X board".