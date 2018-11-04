### Low-Power
Lightweight low power library for Arduino.
Included the ATtiny85 and ATtiny84 as supported devices.

Version: 1.81

Date: 1-nov-2018

Devices Supported:
* ATtiny85, 45, (25)
* ATtiny84, 44, (24)
* ATMega88
* ATMega168
* ATMega168P
* ATMega328P
* ATMega32U4
* ATMega644P
* ATMega1284P
* ATMega2560
* ATMega256RFR2
* ATSAMD21G18A

####Notes:
External interrupt during standby on ATSAMD21G18A requires a patch to the <a href="https://github.com/arduino/ArduinoCore-samd">Arduino SAMD Core</a> in order for it to work. Fix is provided by this particular <a href="https://github.com/arduino/ArduinoCore-samd/pull/90">pull request</a>.
