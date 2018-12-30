# diyHue_PCB-Files
## This is the seperate repo for PCB files for the [diyHue](https://github.com/diyHue/diyHue) project

**Important: The last designs had some bugs that made them unfunctional in the previous state! Only order the updated design!**

There are currently two different board designs available, one is for driving 12v strips without integrated driver ic, and the other is for led strips with WS2812 or SK6812 or similar leds.

Every design uses one 5.5x2.1mm DC Jack for power input.<br>
When choosing the power supply it is very important that the Jumper on the bottom of the pcb is set correctly:

| 5V supply | 12V supply |
|---------------------------|---------------------------|
| connect middle pad to +5V<br>don't solder the buck converter | connect middle pad to EXT<br>**!important!** for the pwm driver the *input voltage* is the same as the *led voltage*! |

| PWM Driver for up to 5 Channels |  |
|----------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------|
| ![5-Channel-PWM-top](https://raw.githubusercontent.com/Nikfinn99/diyHue_PCB-Files/master/images/5channelpwm-top.png) | ![5-Channel-PWM-bot](https://raw.githubusercontent.com/Nikfinn99/diyHue_PCB-Files/master/images/5channelpwm-bot.png) |

|Layout and Schematic | |
|----|-----|
| ![5-Channel-PWM-brd](https://raw.githubusercontent.com/Nikfinn99/diyHue_PCB-Files/master/images/5channelpwm_brd.png) | ![5-Channel-PWM-sch](https://raw.githubusercontent.com/Nikfinn99/diyHue_PCB-Files/master/images/5channelpwm_sch.png)



| WS2812(b) or SK6812 Driver |  |
|-----------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------|
| ![WS2812-top](https://raw.githubusercontent.com/Nikfinn99/diyHue_PCB-Files/master/images/ws2812b-top.png) | ![WS2812-bot](https://raw.githubusercontent.com/Nikfinn99/diyHue_PCB-Files/master/images/ws2812b-bot.png) |

|Layout and Schematic | |
|----|-----|
| ![WS2812-brd](https://raw.githubusercontent.com/Nikfinn99/diyHue_PCB-Files/master/images/ws2812b-brd.png) | ![WS2812-sch](https://raw.githubusercontent.com/Nikfinn99/diyHue_PCB-Files/master/images/ws2812b-sch.png) |
