# ElectroSoul RS485 Modbus Master Liberary for Arduino IDE
===================================================
This is ElectroSoul RS485 Modbus Master Liberary Liberary which works great and has beed tested on ElectroSoul ESP32-RS485 Modbus Gateway.

This Liberary makes it very simple to establish an Industrial Standard RS485 Modbus Communication with OUR ESP32-RS485 Modbus Gateway or any other Arduino compatible board in which you can use TTL to RS485 modules available.
# ElectroSoul ESP32-RS485 Modbus Gateway
<a href="https://www.tindie.com/products/electrosoul/esp32-rs485-modbus-gateway/"><img src="https://electrosoul.in/product_photo/RS485_Gateway_WiFi/Picture1.png" title="ESP32-RS485 Modbus Gateway" alt="ESP32-RS485 Modbus Gateway"></a>
## Development Status
Basic Requirenment are already set for an Industrial RS485 standards with the liberary so that you can directly use the library for your Arduino + RS485 projects.

**UART Support**
  * Liberary supports Hardware UART ✅
  * Software Serial Liberary is also supported ✅
  * Can set different baud rates ✅
  * Data Bit ❌
  * Parity   ❌
  * Stop Bit ❌

**Direction Control for RS485 Transceivers**
  * Any digital pin can be used as Direction control pin ✅

**RS485 Function Code(FC) Supported By Liberary**
  * Read Holding Registers (FC=03)✅
    *read single register✅
    *read multiple register❌
  * Read Input Registers (FC=04)
    *read single register✅
    *read multiple register❌
  * Write Single Coil (FC=05)✅
  * Write Single Register (FC=06)✅
  * Read Coil Status (FC=01)❌
  * Read Input Status (FC=02)❌
  * Write Multiple Coils (FC=15)❌
  * Write Multiple Registers (FC=16)❌

**Additional Liberary Features**
  * Can generate CRC ✅
  * Validate CRC in receiving packet (Note: if CRC fail you will get -88.88) ✅
  * You can set Timeout from .h file default 1 Sec (Note: if  Timeout ocures you will get -99.99) ✅
  
  
  Repository Contents
-------------------

* **/examples** - Example sketches for the library (.ino). Run these from the Arduino IDE. 
* **/src** - Source files for the library (.cpp, .h).
* **library.properties** - General library properties for the Arduino package manager.
  
  
  
  

