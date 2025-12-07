# AP Physics 1 Solver for TI-84 Plus

This directory contains the source code for a modular AP Physics 1 solver designed for the TI-84 Plus (non-CE) graphing calculator.

## Files

- `PHYSICS1.tib`: The main menu program.
- `PHKINE.tib`: Kinematics module.
- `PHDYN.tib`: Dynamics module.
- `PHNRG.tib`: Work & Energy module.
- `PHMOM.tib`: Momentum module.
- `PHROT.tib`: Rotation module.
- `PHSHM.tib`: Simple Harmonic Motion module.
- `PHFLUD.tib`: Fluids module.

## Installation Instructions

1.  **Transfer**: You need TI-Connect software and a USB cable to transfer these files to your calculator.
    - If you have the files in `.8xp` format (compiled), just drag and drop.
    - If you are typing them manually or using a text editor, ensure you use the correct tokens.
2.  **Dependencies**: The programs rely on each other. You must install all files.
3.  **Global Variables**: The programs use global variables (A-Z, Theta). Running these programs will overwrite values stored in these variables.
4.  **Running**: Execute `prgmPHYSICS1` to start.

## Usage

- Navigate the menus using the number keys.
- Enter known values when prompted.
- Enter `0` for the unknown variable you wish to solve for.
- Note: `G` is set to 9.8 and `N` (Newtonian Gravity Constant) to 6.67E-11 automatically.

## Developer Notes

- The code is written in TI-BASIC.
- Files with `.tib` extension are text representations.
- "Stop" command is used to terminate execution after a result is displayed. You will need to restart `prgmPHYSICS1` for the next problem.
