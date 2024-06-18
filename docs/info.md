<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

When two four-bit values are entered into registers A and B the output Y will give you a result based on the Operation being performed.

## How to test

Input a binary value into the A and B registers then select an operation and see the result on the output Y.
      000 : Y = A + B;
      001 : Y = A - B;
      010 : Y = A & B;
      011 : Y = A | B;
      100 : Y = A ^ B;
      101 : Y = ~A;
      110 : Y = A >> 1;
      111 : Y = A << 1;
## External hardware

Some interrupters and LEDS for inputting and seeing the results.
