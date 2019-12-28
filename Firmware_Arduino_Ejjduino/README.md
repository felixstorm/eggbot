# EggDuino / Ejjduino

## Firmware for EggBot with Arduino (Uno) Control Board

Based on:
* Eggduino-Firmware by Joachim Cerny
* https://github.com/cocktailyogi/EggDuino
* https://www.jjrobots.com/sphere-o-bot-jjrobots-version ("Ejjduino_ARDUINO")
* https://github.com/mirkin/eggbot/tree/master/Ejjduino_ARDUINO

Modifications:
* https://github.com/mirkin/eggbot : "Servos speed too fast so used Ejjduino_ARDUINO/ and added VarSpeedServo to save the pen tips."
* fix reversed use of penUpPos and penDownPos
* also save servoRateUp and servoRateDown to EEPROM, use magic number
* also save pen state in EEPROM (for it to survive reboots caused by DTR activation on serial port being opened - apparently almost impossible to avoid especially cross platform)


## License: MIT
