# Half Subtractor using Verilog

## Overview
A Half Subtractor is a combinational logic circuit that subtracts two single-bit binary numbers.

### Inputs
- A
- B

### Outputs
- Difference (D)
- Borrow (Bo)

## Truth Table

| A | B | Difference | Borrow |
|---|---|------------|--------|
| 0 | 0 | 0 | 0 |
| 0 | 1 | 1 | 1 |
| 1 | 0 | 1 | 0 |
| 1 | 1 | 0 | 0 |

## Logic Equations

Difference = A XOR B

Borrow = A' AND B

## Files

- `half_subtractor.v` - Verilog Design
- `half_subtractor_tb.v` - Testbench
- `simulation_output.txt` - Simulation Results
- `waveform.png` - Simulation Waveform

## Software Used

- ModelSim / Vivado / Icarus Verilog
- GTKWave (optional)

## Expected Output

```
A=0 B=0 Difference=0 Borrow=0
A=0 B=1 Difference=1 Borrow=1
A=1 B=0 Difference=1 Borrow=0
A=1 B=1 Difference=0 Borrow=0
```

## Author

Your Name

