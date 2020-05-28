# voicemask
arduino code for my light up face mask

mask can be seen here https://twitter.com/TylerGlaiel/status/1265035386109128704

wiring: arduino nano, 9v battery, 9v to 5v regulator, flexible neopixel grid, electret mic breakout

9v battery to VIN and GND on the arduino  
DIN on the led matrix to 330Ω resistor to digital pin 6 on the arduino  
9v battery to 9v to 5v regulator, to 5v and GND on the led matrix  
Electret mic to A7, 5V and GND on the arduino

guide for the LED matrix says that the power pins should be connected with a 1000uf capacitor, I left this out because I dont want a fat capacitor near my face. no guarantees on the safety of that
