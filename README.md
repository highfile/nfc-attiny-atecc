# nfc-attiny-atecc
Secure element enabled nfc tag, inspired by the SiLo concept of Kong Cash

* NFC: NXP NTAG I2C plus
* Microcontroller: Attiny85V
* Secure Element: ATECC608A

Other than the microcontroller, the primary components are the same as used in Kong Cash. The assumption here (since their design is not open source) is that the mcu acts as a pass-through and doesn't require any special security features itself. All parts on this board are SOIC8 package for ease of hand soldered assembly, but all come in smaller QFN or similar packages for reduced size design.

**Update: Boards sent off for manufacture 3/4/20, COVID-19 likely to cause delays. Firmware to follow.**
