# UART UVM
UVM verification environment for jamieiles's UART on GitHub.

## Checklist
- [x] Set Up DVT for lint
- [x] Set Up DSim for sim
- [x] Reorganize the hierarchy
- [ ] Baseline environment
- [ ] Configuration classes
- [ ] Sequences
- [ ] Scoreboard
- [ ] Coverage
- [ ] Assertions
- [ ] Callbacks

## Original README
Simple verilog UART.

A simple UART for use in an FPGA as a debug engine.  Requires a 50MHz input
clock that gets divided into clock enables for a 16x oversampling receiver
clock enable and 115200 baud transmission clock enable.

Icarus verilog testbench verifies that each byte can be sent correctly, but
does not do anything with spacing between bytes.

Licensed under GPLv2.

