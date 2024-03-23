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

A Full Subtractor circuit is an essential component in digital electronics, particularly in arithmetic circuits. It takes three inputs: minuend (A), subtrahend (B), and borrow-in (BIN). It produces two outputs: difference (DIFF) and borrow-out (BOUT).

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
