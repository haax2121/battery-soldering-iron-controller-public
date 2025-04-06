# battery-soldering-iron-controller
Industrial display design with very good readability even for a user at a considerable distance.  The display is built with 16 8x8 pixel matrix indicators with dimensions of 32x32mm.  For each indicator there is a dedicated MAX7219 controller. The controllers are connected in cascade, making control of the entire display possible using a single SPI line (MOSI, SCK, CS).  The designed display has dimensions of 250mm by 64mm. The operation of the designed device is controlled by a PIC32MX470 microcontroller. The PCB design was created in Altium Designer. The software was written in C using the MPLABX IDE development environment. 

<img src="working.gif" width="800">
<img src="menu.gif" width="800">
<img src="image_1.jpg" width="800">
<img src="image_2.jpg" width="800">
<img src="image_3.jpg" width="800">
<img src="hardware/pcb3.png" width="800">
<img src="hardware/pcb4.png" width="800">
