# <u>**Cabled DS18B20**</u>

<img src="img/DS18B20-cabled.png" width="50%" > 

**Description**  
Cabled DS18B20 temperature sensor

**Pinout**
* GND
* S : Signal wire. 
* VCC : 5V Power supply wire

**Software control**
Communicate by 1-wire protocol, that can be managed conneting the S signal to a digital pin working as I/O.
On the S pin a pull-up resistor 4.7K 1/4W  is required. Is not recommended to use internal micro internal pull-up as it's usually too big for the speed required by 1-wire protocol.

**Sourcing**  
  
* [Google] : search "cabled DS18B20".