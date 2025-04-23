# 5-Stage Pipelined MIPS Processor

This project implements a 32bit five-stage pipelined processor in Verilog. It contains modules for an ALU, Control Unit, Register File,and separate pipeline registers for each stage of a RISC-based MIPS pipeline: Instruction Fetch, Instruction Decode/Register Fetch, Execute, Memory Access, and Write-Back.

## Running the Project

Xilinx Vivado is required. From the repository root, run:

```sh
vivado -nolog -nojournal -mode batch -source vivado.tcl
```

The script adds the RTL/testbench files and sets `core_tb` as the simulation top, then opens the Vivado GUI.

## Contributors

- Varun C (2021B3AA3031H)
- Palaniappan R (2021B4AA2915H)
- Sai Anirudh Kota (2021B5AA2287H)
- D Muruga Perumal (2021A8PS1895H)

All authors contributed equally. The project was developed at BITS Pilani,
Hyderabad Campus.

## License

This project is licensed under the GNU General Public License v3.0. See
[LICENSE](LICENSE) for details.
