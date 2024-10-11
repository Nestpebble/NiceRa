## Sidekick Breakout V2.0

### V2.0 Full-size board
This has 3 options for adding battery voltage sense resistors:
1) two thru-hole resistors (ratio 2:3, e.g. 220k & 330k)
2) two 1206 size SMD resistors (e.g. 750k & 500k)
Secret hidden option 3) two 0805 resistors on the same footprint as the 1205

This has 4 options for Reset and User buttons:
1) 2x 6x6mm SMD tactile switches on the radio module side
2) 2x 6x6mm thru-hole switches with two legs cut off on the radio module side
3) 2x 3.5x6mm SMD tactile switches on the Pro-Micro side
4) 2x 3x4mm SMD tactile switches on the Pro-Micro side
Secret hidden option 5) A 4.5x4.5mm thru-hole tactile switch can be placed between pins 23 & 24 (i.e. RST and GND) on the radio module side.

![Nice-ra sidekick V2.0 button options ](./Sidekick_V2.0.png)

### How to order
1) Take the zip folder with the Gerber files in
2) Upload it to the PCB fabricator of your choice (I've put placeholder text for JLCPCB order numbers on the board, but this is covered by the radio module once assembled)
3) Select surface finish, PCB thickness, and other options
4) I've tested these boards at 1.0mm thickness, and they work ok. Thicker is better, but obviously translates directly into node size
