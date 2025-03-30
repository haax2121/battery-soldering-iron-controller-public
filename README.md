# battery-soldering-iron-controller
Battery soldering iron controller base on STM32G0 MCU. Controller was made to use with T210 and T245 handles from AiXun.
Device use 2.4" LCD (240x320) to display soldering state. Operation of device is controlled by a rotary encoder. Device support any T210 and T245 handler from AiXun with optional stand control. The tool can operate from 12V to 24V, but the default assumption was to work with batteries used in various power tools, e.g. Parkside, Bosch. The PCB project was made in Altium Desginer 21. Software was writen in C with HAL API using STM32CubeIDE.

<img src="working.gif" width="500" alt="">
![Image](https://github.com/haax2121/battery-soldering-iron-controller/blob/main/working.gif)
![Image](https://github.com/haax2121/battery-soldering-iron-controller/blob/main/menu.gif)
![Image](https://github.com/haax2121/battery-soldering-iron-controller/blob/main/image_1.jpg)
![Image](https://github.com/haax2121/battery-soldering-iron-controller/blob/main/image_2.jpg)
![Image](https://github.com/haax2121/battery-soldering-iron-controller/blob/main/image_3.jpg)

