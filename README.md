

# Lampi Smart Light

## Description

LAMPI is an RGBWW WiFi LED smart light based on ESP8266, there is an INA219 energy sensor on the board that enables it to measure the battery voltage and the energy consumption and maintain the light intensity when the battery voltage changes. It also protects LEDs from overheating by measuring the temperature of the LED board.

### Hardware Features:

- 3 - 16V Wide input voltage range (using batteries).
- 5 dedicated PWM outputs for red, green, blue, warm white, and cold white LEDs.
- Up to 2.5A current capability for each channel.
- 20kHz PWM frequency which eliminates ringing noise, and flickering effects.
- 3 digital inputs for connecting to rotary encoders or individual buttons.
- MCP1700T-3302 & MCP1703A-3302, low quiescent current LDO design providing suitable voltage for ESP8266 for different input voltages.
- I2C output pins to connect to external components such as I2C LCDs. 
- NTC temp sensor on LED board
- Separate ESP board and LED design for better thermal protection and better WiFi signal range.
- Serial header pins for programming and debugging.
- 66 pcs 2835 (0.1 to 1W) (3 to 12V)  SMD LED board design.
- Compact design.
- Compatible with [ESPurna Firmware](https://github.com/xoseperez/espurnahttp:// "ESPurna Firmware") which adds lots of features to this Smart LED Light.

Check out this video for more information. 

[![](https://img.youtube.com/vi/hzMJHiyabQk/0.jpg)](https://youtu.be/hzMJHiyabQk)

## To access schematic and pcb files check [here](https://oshwlab.com/hamedta/lampii)



[![](https://github.com/hamed-ta/LAMPI/blob/main/images/Overview_1.jpeg)](https://github.com/hamed-ta/LAMPI/blob/main/images/Overview_1.jpeg)
[![](https://github.com/hamed-ta/LAMPI/blob/main/images/Overview_2.jpeg)](https://github.com/hamed-ta/LAMPI/blob/main/images/Overview_2.jpeg)
[![](https://github.com/hamed-ta/LAMPI/blob/main/images/Overview_3.jpeg)](https://github.com/hamed-ta/LAMPI/blob/main/images/Overview_1.jpeg)

![enter image description here](https://github.com/hamed-ta/LAMPI/blob/main/images/ESP_Schematic.png)
![enter image description here](https://github.com/hamed-ta/LAMPI/blob/main/images/ESP_Board_Tracks.png)
![enter image description here](https://github.com/hamed-ta/LAMPI/blob/main/images/ESP_Board_Front_With_Components.png)

![enter image description here](https://github.com/hamed-ta/LAMPI/blob/main/images/ESP_Board_Back_With_Components.png)
![enter image description here](https://github.com/hamed-ta/LAMPI/blob/main/images/ESP_Board_Front_Without_Components.png)
![enter image description here](https://github.com/hamed-ta/LAMPI/blob/main/images/ESP_Board_Back_Without_Components.png)
![enter image description here](https://github.com/hamed-ta/LAMPI/blob/main/images/LED_Board_Schematic.png)
![enter image description here](https://github.com/hamed-ta/LAMPI/blob/main/images/LED_Board_Front_Tracks.png)
![enter image description here](https://github.com/hamed-ta/LAMPI/blob/main/images/LED_Board_Front_With_Components.png)
![enter image description here](https://github.com/hamed-ta/LAMPI/blob/main/images/LED_Board_Front_Without_Components.png)
![enter image description here](https://github.com/hamed-ta/LAMPI/blob/main/images/LED_Board_Back.png)
