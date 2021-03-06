canbus-stellaris
================

Working example of CAN BUS for Stellaris Launchpad (EK-LM4F120XL)
* Install required software tools
* Setup hardware
* Import, Build and Debug Code Composer projects 

Project Page
============
http://murix.github.io/canbus-stellaris/

Developer Page
==============
http://dronespersonalizados.blogspot.com.br/


Required software tools
=======================

* Code Composer Studio 5.5 (http://www.ti.com/tool/ccstudio)
* StellarisWare 9453 (http://www.ti.com/tool/sw-ek-lm4f120xl)


Required hardware
=================

* 2 x Stellaris Launchpad (EK-LM4F120XL)
* 2 x Microchip MCP2551 (http://www.microchip.com/mcp2551)
* 2 x 1k ohm resistor
* 2 x 120 ohm resistor
* 10 x Breadboard Jumper Cable Wires Male (http://dx.com/s/Jumper+wire+male)
* 1 x Breadboard (http://dx.com/s/breadboard)

Notes
=====
* Stellaris Launchpad GPIOs are 5V tolerant
* Stellaris Launchpad to avoid possible short-circuit remove R9 and R10

CAN BUS Schematic

![canbus schematic](canbus-schematic.png)

Reference hardware setup

![hardware setup canbus](canbus-stellaris-mcp2551.jpg)

Excepted console output ( COM9 is CAN TX / COM4 is CAN RX )

![console output](canbus-stellaris-console.JPG)








