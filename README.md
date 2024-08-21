# Electonic-Voting-Machine-using-Arduino.UNO


## Overview
This project is a basic electronic voting system with a login password. It uses an Arduino UNO, Oled display, 3 LEDs, 3 pushbuttons, and jumper wires. The system allows users to vote and view results.

## Getting Started

### Prerequisites
- Arduino IDE installed
- Arduino UNO board
- Oled display
- 3 LEDs
- 3 Pushbuttons
- Jumper wires

### Setup
1. Connect components according to the circuit diagram.
2. Upload the provided code (evm.ino) to your Arduino UNO using the Arduino IDE.

## Usage

### 1. Login
- Power on the EVM.
- Enter the login password displayed on the Oled to proceed.

### 2. Main Menu
- Choose between **Voting** and **Results** using the pushbuttons.

### 3. Voting
- Select **Voting** and enter your Voter ID.
- Choose your candidate (Virat, Dhoni, Sachin) by pressing the corresponding pushbutton.
- A confirmation message will appear, and you can vote again or view results.

### 4. Results
- Select **Results** and re-enter the login password.
- The display will show the total votes and announce the winner.

## Notes
- Ensure secure connections before powering on.
- The code (evm.ino) contains all necessary logic and can be modified as needed.

Happy Voting!
