# Digital Systems Design Final Project -- Imitation Game on FPGA
### By Eric Trostin and Isar Doshi

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Getting Started](#getting-started)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)

## Introduction

The VHDL code provided in this repository implements a simple imitation game with a display that shows different patterns. The objective is for the player to follow the displayed pattern by clicking the corresponding buttons. The code consists of several VHDL modules working together to create the game logic, manage levels, generate random patterns, and drive the seven-segment display.

## Features

### 1. Imitation Game

The code implements a basic imitation game where the player must mimic a displayed pattern using directional buttons. The pattern changes based on the switches that are currently flipped on the board.

### 2. Game Levels

Multiple levels provide a progressive challenge for the player, with patterns of increasing complexity.

### 3. Pseudo-Random Number Generation (PRNG)

Utilizes a PRNG - A Pseudo-Random Number Generator based to generate random patterns for the game.

## Getting Started

* Begin by flipping up a random amount of switches and then pressing BTNC to start

## Prerequisites

* Vivado
* Nexys Artix A7-100t
* Micro USB Cable
* Zip folder containing this project

## Installation

1. Download and extract files from ZIP folder
2. Open Vivado and open project - point project directory to the location of the downloaded folder
3. Select .xpr file to open project
4. Run synthesis, implementation, generate bitstream and program device

## Usage

* Repeat patterns appearing on the screen using the 4 buttons - BTNU, BTNR, BTND, BTNL
  

