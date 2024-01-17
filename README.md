# Gravity I2C SD2405 RTC Module

Gravity I2C SD2405 RTC Module Respository, including library, sample code, Schematic & layout<br>

Contains the Following:

* Arduino library: GravityRtc
* Arduino library.zip: GravityRtc.zip
* Schematic.pdf: Gravity I2C SD2405 RTC Module Schematic.pdf
* Layout.pdf: Gravity I2C SD2405 RTC Module Layout.pdf
* Datasheet: SD2405AL datasheet.pdf

[Get the RTC Module here](https://www.dfrobot.com/wiki/index.php/Gravity:_I2C_SD2405_RTC_Module_SKU:_DFR0469)

To Download, please click "Clone & Download ZIP"

## Issues

We encoutered several issues with the code from [Gravity-I2C-SD2405-RTC-Module on GitHub](https://github.com/DFRobot/Gravity-I2C-SD2405-RTC-Module) as the suttle differences from the much more common library "RTC.h" cause work to rewrite code in several projects we had tried to use. We reverted to using the much more common "RTC.h".

And the Gravity-I2C-SD2405-RTC-Module code was not in platformio and we cannot stand the Adrunio IDE.

[Arduino UNO R4 WiFi Real-Time Clock](https://docs.arduino.cc/tutorials/uno-r4-wifi/rtc) has samples and explainations of using RTC that is built in to Arduino UNO R4 WiFi.
