# NFC2USB

Connect an RC522 based NFC-Reader to your computer using USB

The project is based around an [ESP32-S2FH4](https://www.espressif.com/sites/default/files/documentation/esp32-s2_datasheet_en.pdf) with it's most basic support components and no RF circuitry since we just need GPIO and processing power. It would have been possible to solve this with a much simpler microcontroller but availability and pricing at the time of development made the ESP32 with built in USB and flash the best choice. 

The board is designed using KiCAD 6 with production and assembly by JLCPCB in mind. All parts are selected to be available from JLCPCB at the time of writing and as many parts as possible are used from their basic library.