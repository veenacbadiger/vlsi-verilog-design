# Half Adder

A basic combinational logic circuit that performs binary addition of two 1-bit inputs.

## Design

The Half Adder has two inputs and two outputs:

* **Inputs:** A, B
* **Outputs:** Sum, Carry

### Boolean Expressions

```text
Sum   = A XOR B
Carry = A AND B
```

## Truth Table

| A | B | Sum | Carry |
| - | - | --- | ----- |
| 0 | 0 | 0   | 0     |
| 0 | 1 | 1   | 0     |
| 1 | 0 | 1   | 0     |
| 1 | 1 | 0   | 1     |

## Files

* `half_adder.v` — Verilog RTL design
* `tb_half_adder.v` — Verilog testbench

## Tools

* Verilog HDL
* ModelSim
* Intel Quartus Prime

## Verification

The testbench applies all four possible input combinations and verifies the corresponding Sum and Carry outputs.
