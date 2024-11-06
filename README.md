# Palamedes: Autonomous Chess-Playing SCARA Robot

## Overview

**Palamedes** is a SCARA robot designed to autonomously play chess against a human opponent. This project combines electronics, programming, and computer vision to create a fully functional robot capable of detecting board states, strategizing moves, and physically manipulating chess pieces.

## Project Features

- **Board State Detection**: Uses computer vision to capture images of the chessboard, detect individual squares, and map their coordinates.
- **Move Tracking**: Compares before-and-after images to track human moves, updating piece positions and integrating with the Stockfish chess engine.
- **Chess Strategy**: Stockfish engine calculates optimal moves, allowing Palamedes to respond accurately to player moves.
- **Hardware Control**: Python script manages GUI, image comparison, serial communication, and game tracking; Arduino Mega and RAMPS 1.4 board control motors and switches for precise movement.
