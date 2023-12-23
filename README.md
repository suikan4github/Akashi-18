# Akashi-18
Pico Trainer : Raspberry Pi Pico board with full color LED.

# Details
To provide much fan for the first-day trainee, using full color LED. 

The PCB employs followings : 
Parts              | QTY
-------------------|-----
Full Color LED     | 1
Push button Switch | 3
Potentiometer      | 1


The following table shows the pin connections. 

Color | GPIO 
------|--------
Red   | 20
Green | 21
Blue  | 22

Each GPIO is active Hi. That means, 
Output "H" signal to turn on the LED.

There are three user switches : 

Switch | GPIO
-------|------
SW1    | 11
SW2    | 12
SW3    | 13

All switches are active Lo. That means, pushing down the switch makes
the GPIO input to "L". 

The potentiometer is connected to ADC0. 

# Additional documents
- [Schematics](doc/Akashi-18.pdf)
- [Parts list](doc/partslist.ods)

# Gallery
