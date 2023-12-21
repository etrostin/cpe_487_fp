# Digital Systems Design Final Project -- Imitation Game on FPGA

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The VHDL code provided in this repository implements a simple imitation game with a display that shows different patterns. The objective is for the player to follow the displayed pattern by clicking the corresponding buttons. The code consists of several VHDL modules working together to create the game logic, manage levels, generate random patterns, and drive the seven-segment display.

## Features

### 1. Imitation Game

The code implements a basic imitation game where the player must mimic a displayed pattern using directional buttons.

### 2. Game Levels

Multiple levels provide a progressive challenge for the player, with patterns of increasing complexity.

### 3. Pseudo-Random Number Generation (PRNG)

Utilizes a Pseudo-Random Number Generator (PRNG) based on a linear feedback shift register to generate random patterns for the game.

### 4. Seven-Segment Display (SSD) Driven

Drives a seven-segment display to visually represent the patterns to the player.

### 5. Timer Functionality

Implements a timer with multiple timeout settings, contributing to the game's challenge.

### 6. Debouncing

Includes debouncing mechanisms for input signals to ensure stable and noise-free button presses.

### 7. Input Encoding

Encodes directional button inputs to accurately determine the player's intended direction.

### 8. Red Filter

Applies a red filter to the input signal, potentially for visual effects or enhancing user experience.

### 9. Modular Design

Organizes the code into several VHDL modules, each responsible for specific functionalities such as game logic, PRNG, display driving, timer, debouncing, etc.

### 10. Top-Level Integration

The `Top_level` module integrates all components to create the complete game logic.

### 11. Scalability

The design is potentially scalable, allowing for easy expansion or modification of features.

### 12. Testbench

A testbench (`ssd_tb.vhd`) is provided for the SSD module, facilitating verification and testing.

### 13. Clear Documentation

The README file provides clear documentation on each VHDL module, including their purpose, ports, and functionalities.

### 14. Clock and Reset Handling

Manages clock and reset signals appropriately to synchronize and initialize the game components.

### 15. Readability and Maintainability

Code is structured to enhance readability and maintainability, with descriptive module names and clear organization.

### 16. Flexible Configuration

The code allows for flexible configuration through various input signals, supporting adaptability to different scenarios.

### 17. Comments

Includes comments within the code for better understanding and to guide developers during maintenance or modification.

## Getting Started

Explain how to get started with the project, including any prerequisites and installation instructions.

### Prerequisites

List any software, libraries, or tools that users need to have installed before using the project.

### Installation

Provide step-by-step instructions on how to install and set up the project.

## Usage

Explain how to use the project, including examples or code snippets if applicable.

## Contributing

Provide guidelines for those who want to contribute to the project. This could include information on how to report issues, submit feature requests, or contribute code.

## License

Specify the project's license, along with any additional terms or conditions.

