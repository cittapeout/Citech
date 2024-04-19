<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

Workwi project using a D flipflop ring to display "CIt" on the 7 segment display.

## How to test
Start with all input switches off,
and sliding switch to the left
(i.e. to select the automatic clock pulse and turn on 1st switch).
The letters "C" "I"  "t" will start to blink with delay

Switch on input switch 1, and "C" will be displayed.

Switch on input switch 2, and "i" will be displayed

Switch on input switch 3, and "t" will be displayed
## Notes

These are the inputs:

| In  | Signal | Function                       |
|-----|--------|--------------------------------|
| SW1 | IN0  | *Run*: Off = Reset; On = Run     |
| SW2 | IN1  | state_init[0]; Normally ON       |
| SW3 | IN2  | state_init[1]; Normally off      |
| SW4 | IN3  | state_init[2]; Normally off      |
| SW5 | IN4  | state_init[3]; Normally off      |
| SW6 | IN5  | (Unused)                         |
| SW7 | IN6  | (Unused)                         |
| SW8 | IN7  | (Unused)                         |

## External hardware

None,beside the TT demo board.
