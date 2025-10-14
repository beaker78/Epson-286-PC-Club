This PCB is an interface to connect a Gotek to an EPSON PC-286C "PC-Club" using it's internal ribbon cable. 

Umechan's retro ACTIVE (@umechans_retroactive) had already done the reverse engineering in this fantastic video https://www.youtube.com/watch?v=hA0FdqVGhqE, 
and I wanted to an excuse to try and design a simple PCB having zero experience. Please note, I am a software developer by trade with no engineering background so
feel free to correct all my mistakes.

The FPC FFC flat cable socket to connect the ribbon cable to the PCB should be soldered so it is on the bottom side of the PCB, 
and the floppy header and power connectors for the Gotek should be soldered on the top side of the board. I have attempted to show pin numbers along with the 
input and output of each pin (abbreviated badly) to help with any clarification/diagnosis.

You may also wish to make your own short floppy data and power cables to the gotek as space is at a premium. I have included a 3D print stl of the sandwich I used to
offset both boards slightly and it just about fits in the space available. 

If you plan of redesigning the board I would reduce the width even more, especially if you plan to replace both floppy drives with Goteks.

BOM:

FPC FFC 1.25mm pitch flat cable socket. I ordered from AliExpress right angle (A-02) 26 pin connectors. Please note the cable pitch. 
The more standard 0.5mm and 1mm pitches will be too small.
https://www.aliexpress.com/item/1005002262284714.html

2.54mm Double Row Male Headers which I cut to the correct length
https://www.aliexpress.com/item/1005006870659706.html

Mini 4 pin 2.54mm pitch (floppy) right high angle socket
https://www.aliexpress.com/item/1005004647707706.html

Please note, while I am not an expert in anyway, I welcome any feedback. If you wish to make this you do so at your own risk.
