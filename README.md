# Cube-Computer

## Overview
Cube-Computer is an innovative project featuring a computer system designed using Logisim, a tool for visualizing and simulating digital logic circuits. This project introduces a custom-built computer that interprets its own language specifically crafted to manipulate a cube displayed on a 2D screen.

## Features
- **Custom Language and Processor**: Utilizes a unique set of instructions embedded within a binary file to control cube operations.
- **Schematic Design**: Developed using Logisim to provide a clear and interactive representation of the computer's architecture.
- **GPU and CPU Integration**: Features a rudimentary CPU and GPU built from scratch, capable of manipulating and rendering 128 points in parallel to display the cube.
- **Commands**: Supports four basic commands:
  - Rotate the cube 5 degrees on the X-axis
  - Rotate the cube 5 degrees on the Y-axis
  - Do nothing (NOP)
  - Jump to Line 0 (reset sequence)
  
  Each command is represented by a concise 2-bit code within the binary file.

- **Interactive Controls**: Includes a 'Load' button that resets the cube to its predefined orientation, facilitating easy visualization and control.

## Usage
To interact with the Cube-Computer, load the provided binary file using the Logisim software. This file contains the encoded commands that guide the cube's movements and behavior on the screen.

## Getting Started
1. **Download Logisim**: Ensure you have Logisim installed on your computer to open and run the project files.
2. **Clone the Repository**: Download or clone this repository to get access to the schematic files.
3. **Load the Schematic**: Open the schematic in Logisim and load the binary file to start manipulating the cube.

