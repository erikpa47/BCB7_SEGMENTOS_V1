<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

This project implements a BCD-to-seven-segment decoder. It receives a 4-bit input and converts it into an 8-bit output to control a seven-segment LED display. The output signals determine which segments of the display are activated to represent the corresponding digit.

## How to test

To test the design, apply different 4-bit input values and verify that the seven-segment display shows the corresponding digits. Observe the LED display to confirm that the output signals correctly activate the required segments for each input value.

## External hardware

This project uses a seven-segment LED display. The input consists of a 4-bit signal, and the output consists of an 8-bit signal used to control the display segments and additional output.
