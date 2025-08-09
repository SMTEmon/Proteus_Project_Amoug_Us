# Proteus Project: Among Us Reactor Task (DLD Logic, No Microcontroller)

## Overview

This project is a simulation of the "Reactor Task" from the game **Among Us**, implemented in Proteus using only Digital Logic Design (DLD) components—completely **without any microcontroller** or programming. The objective is to replicate the sequential button-press mini-game found in Among Us, showcasing how such logic can be built using fundamental digital logic circuits.

## Features

- **No Microcontroller:** The task logic is implemented entirely with DLD components (logic gates, counters, flip-flops, LEDs, etc.).
- **Game Simulation:** Mimics the original Among Us reactor task, requiring users to repeat a sequence of button presses as indicated by LEDs.
- **User Interaction:** Switches act as user input buttons; LEDs provide feedback for correct or incorrect input.
- **Educational Value:** Demonstrates sequential and combinational logic design in a fun, game-themed context.

## How It Works

1. **Sequence Generation:** A random or preset sequence of LED flashes is created using counters and logic gates.
2. **User Input:** The user must replicate the sequence using switches.
3. **Validation:** The logic circuit checks the user's input against the generated sequence.
4. **Feedback:** LEDs indicate whether the input is correct (progresses the game) or incorrect (resets the sequence).

## Getting Started

1. **Clone this Repository:**
   ```bash
   git clone https://github.com/SMTEmon/Proteus_Project_Amoug_Us.git
