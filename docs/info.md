## How it works

This project implements a 1-bit half adder.

A half adder adds two 1-bit binary inputs:
- x
- y

It produces two outputs:
- S = Sum
- C = Carry

The logic is:
- S = x XOR y
- C = x AND y

This is a combinational circuit because the outputs depend only on the current input values.

## How to test

Apply all 4 input combinations and verify the outputs:

| x | y | S | C |
|---|---|---|---|
| 0 | 0 | 0 | 0 |
| 0 | 1 | 1 | 0 |
| 1 | 0 | 1 | 0 |
| 1 | 1 | 0 | 1 |

## External hardware

None

## Pinout

### Inputs
- ui[0] = x
- ui[1] = y

### Outputs
- uo[0] = S
- uo[1] = C
