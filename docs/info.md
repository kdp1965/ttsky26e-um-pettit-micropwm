## How it works

This is a very simple Wokwi example that uses the 7-Segment display to show a 3-segment "snake" as it
moves around the display.  It uses three 3-bit registers to store the current location of the
"head", "body" and "tail", along with a register identifying the direction (0=clockwise, 1=counter clockwise).

There is also a Linear Feedback Shift Register (LFSR) to randomize the direction of travel.

## How to test

Supply a 10 KHz clock.  Watch the snake move around.  Try different clock speeds.

## External hardware

Only need the 7-Segment display on the demo board.

