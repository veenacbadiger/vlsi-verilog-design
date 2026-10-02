# Half Adder

A basic combinational logic circuit that adds two 1-bit binary inputs.

## Design

**Inputs:** A, B
**Outputs:** Sum, Carry

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
* `half_adder_waveform.png` — ModelSim simulation waveform
* `half_adder_synthesis.png` — Quartus Prime synthesis result

## Tools

* Verilog HDL
* ModelSim
* Intel Quartus Prime

## Verification

The Half Adder was verified using ModelSim for all four input combinations and synthesized successfully using Intel Quartus Prime.
