MiniArcade

[![MiniArcade video](https://www.youtube.com/watch?v=UotAsQmeLYA/0.jpg)](https://www.youtube.com/watch?v=UotAsQmeLYA)

Hardware:
	- Raspberry pi 3 
	- Custom PCB for controller and leds (Schematic folder)
	- Display: BT035ABCBHB352a$ (3.5" Color TFT-LCD video module.)
	
Software:
	- Retropie


How to connect PCB to RB Pi:
https://github.com/adafruit/Adafruit-Retrogame
https://learn.adafruit.com/retro-gaming-with-raspberry-pi/adding-controls-hardware
http://www.instructables.com/id/Make-Joystic-for-Retropie/

MiniArcade config:
	GPIO06 - B
	GPIO12 - LED
	GPIO13 - START
	GND    - GND
	GPIO19 - A
	GPIO16 - LEFT
	GPIO26 - DOWN
	GPIO21 - RIGHT