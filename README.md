# Bin Packing Solver (MIPS Assembly)

## Authors
- [@raghadjam](https://github.com/raghadjam)
- [@may1001sam](https://github.com/may1001sam)

## Overview

This project is a command-line tool implemented in **MIPS Assembly** that solves the Bin Packing Problem using two heuristic algorithms: **First-Fit (FF)** and **Best-Fit (BF)**. The program reads item weights from a user-provided input file (with values between `0.0` and `1.0`), stores them into memory, and organizes them into bins of size `1.0` according to the selected algorithm. The results are written to an output file.

## Features

- File I/O in MIPS: Read item data from file and write results to an output file.
- Floating point parsing and validation.
- Dynamic memory management for storing items and bins.
- Interactive console-based menu.
- Support for:
  - **First-Fit**: Places items in the first available bin.
  - **Best-Fit**: Places items in the tightest-fitting bin.

## How to Use

1. Run the program in a MIPS simulator (e.g. MARS).
2. Enter the name of the input file when prompted.
3. Select the algorithm (`FF` or `BF`).
4. The result will be saved to a predefined output file path.

## Conclusion

This project tackled the classic Bin Packing problem using MIPS assembly language, reinforcing low-level programming skills and algorithmic thinking. By implementing both First-Fit and Best-Fit strategies.
