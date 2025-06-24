This is a modified version of the tagtuner from luka6000 -> https://github.com/luka6000/TagTuner I modified the STL files with thinkercad so i could fit in a small display.

There is a esphome config part and a homeassistant blueprint to send information to the screen.

I used a small st7789v 240x240 screen, and it shows the currently playing artist/title and when you change the volume.
I'm using a esp32 WROOM (https://www.hobbyelectronica.nl/wp-content/uploads/2021/11/D1_mini_esp32_schema.jpg)

st7789v		esp32

```
BLK	->	TDI
DC	->	I16
RES	->	TCK
SDA	->	IO4
SCK/SCL	->	TMS
VCC	->	3.3V
GND	->	GND
```
