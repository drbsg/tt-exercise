<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

This is a simple circuit that adds two 4-bit binary numbers. The first four input pins (REG0_0 to REG0_3)
encode the first binary number, and the second four input pins (REG1_0 to REG1_3) encode the second.
The result appears on four output pins RESULT_0 to RESULT_3, with overflow on the fifth pin OVERFLOW.

## How to test

Cycle through all four bit numbers and check that the arithmetic is working.

## External hardware

None required.
