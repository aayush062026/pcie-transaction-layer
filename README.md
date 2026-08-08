# pcie-transaction-layer

PCIe Transaction Layer: TLP arbiter and ECRC/LCRC reference RTL over AMBA AXI.

## Overview

Reference implementation of a PCIe Transaction Layer, covering TLP arbitration, DLLP integrity handling, and ECRC/LCRC generation and checking, interfacing over AMBA AXI. Built as a portfolio piece; not derived from any employer or client codebase.

## Planned Features

TLP arbiter with configurable prioritization. ECRC generation and checking. LCRC generation and checking. AXI-facing interface wrapper.

## Architecture

See docs/ARCHITECTURE.md for the design write-up and docs/BLOCK_DIAGRAM.md for the block diagram.

## Repository Structure

docs/ contains architecture and block diagram documentation. src/rtl/ contains SystemVerilog and Verilog source. src/tb/ contains testbenches and the verification environment.

## Status

Work in progress, portfolio reference implementation.

## Tools

SystemVerilog, Verilog, QuestaSim

## License

MIT, see LICENSE
