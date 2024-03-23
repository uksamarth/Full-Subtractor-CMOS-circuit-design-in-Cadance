# Full Subtractor Circuit Design in Cadence

This repository contains the design files and documentation for a Full Subtractor circuit implemented in Cadence. The Full Subtractor circuit is a digital logic circuit that performs subtraction of two binary numbers, including borrowing from the previous stage if necessary.

## Table of Contents

- [Introduction](#introduction)
- [Design Files](#design-files)
- [Simulation](#simulation)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

A full subtractor is a combinational circuit that performs subtraction of two bits, one is minuend and other is subtrahend, taking into account borrow of the previous adjacent lower minuend bit. This circuit has three inputs and two outputs. The three inputs A, B and Bin, denote the minuend, subtrahend, and previous borrow, respectively. The two outputs, D and Bout represent the difference and output borrow, respectively. Although subtraction is usually achieved by adding the complement of subtrahend to the minuend, it is of academic interest to work out the Truth Table and logic realisation of a full subtractor; x is the minuend; y is the subtrahend; z is the input borrow; D is the difference; and B denotes the output borrow. The corresponding maps for logic functions for outputs of the full subtractor namely difference and borrow.

This repository provides the schematic, layout, and simulation files for the Full Subtractor circuit designed using Cadence tools.

## Design Files

- `schematic`: Contains the schematic design of the Full Subtractor circuit in Cadence.
- `layout`: Includes the layout design of the Full Subtractor circuit.
- `simulation`: Contains simulation files to validate the functionality of the Full Subtractor circuit.
- `scripts`: Includes any scripts used for automation or post-processing of the design.

## Simulation

The `simulation` directory contains simulations performed on the Full Subtractor circuit to ensure its correct operation under various conditions. The simulations include:

- Input testing with different combinations of A, B, and BIN.
- Propagation delay analysis.
- Power consumption analysis.
- Noise margin analysis.

To run the simulations, follow the instructions provided in the respective simulation files.

## Results

The results obtained from the simulations demonstrate the functionality and performance of the Full Subtractor circuit. These results include:

- Waveform plots showing the inputs (A, B, BIN), outputs (DIFF, BOUT), and internal signals.
- Timing diagrams illustrating the propagation delays and critical paths.
- Power consumption estimates.
- Noise margin analysis to assess circuit robustness.

## Contributing

Contributions to this project are welcome. If you find any issues or have improvements to suggest, please open an issue or pull request on GitHub.

Before contributing, please review the [contribution guidelines](CONTRIBUTING.md).

## License

This project is licensed under the [MIT License](LICENSE), which means you are free to use, modify, and distribute the code as long as you include the original license and attribution.
