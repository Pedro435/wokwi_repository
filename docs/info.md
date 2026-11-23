<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

This project implements a custom combinational logic circuit with three inputs (A, B, C) and two outputs (S and Cout).

The circuit uses NOT, AND and OR logic gates.

The output S is defined by the following Boolean expression:

[
S = AB + A\overline{C} + B\overline{C}
]

The second output is defined as:

[
Cout = C
]

The circuit evaluates the input signals and generates both outputs according to these logical expressions.

## How to test

Open the Wokwi project using the configured Wokwi ID.

Apply all eight possible combinations of inputs A, B and C.

Observe the outputs S and Cout.

Compare the observed outputs with the expected truth table.

Verify that both outputs follow their corresponding Boolean expressions.

## External hardware

No external hardware is required for the logic simulation.

The circuit is simulated using logic gates and a seven-segment display in Wokwi for output visualization.
