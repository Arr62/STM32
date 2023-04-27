# STM32_digital_spirit_level
This project was to create a simple digital spirit level using STM32F446RE MCU. 
An accelerometer was used, with which the MCU communicates using I2C. 
The data from the accelerometer is processed and then the LEDs indicate compliance with the level.

Used elements:
- 13x resistor 220 [Ω]
- 6x red LED, 4x yellow LED, 3x green LED
- accelerometer ADXL345

Scheme:

![scheme](https://user-images.githubusercontent.com/109549335/234984859-d0503388-5f8b-46ce-ade0-52db96c0c12a.png)

Additionally, UART communication was used, through which data about the measured accelerations in three axes are sent.
In this project, RealTerm software was used to read data sent via UART.

Sample read data:

![realterm 1](https://user-images.githubusercontent.com/109549335/234993687-b7995822-0956-4758-a505-ad575570d530.png)
