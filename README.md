# Electonic-Voting-Machine-using-Arduino.UNO

Welcome to the Electronic Voting Machine (EVM) repository using Arduino UNO, Oled display, 3 LEDs, three pushbuttons, and jumper wires.

## Overview

This project implements a basic electronic voting system that requires a login password for access. It utilizes an Arduino UNO, an Oled display, three LEDs, and three pushbuttons labeled 1, 2, and 3. The system offers two main functionalities: voting and viewing results.

## Getting Started
### 1. Prerequisites

* Arduino IDE installed on your computer.
* Arduino UNO board.
* Oled display.
* 3 LEDs.
* 3 Pushbuttons.
* Jumper wires.
  
### 2. Setup
* Connect the components as per the circuit diagram provided.
* Open the Arduino IDE and upload the provided code (evm.ino) to your Arduino UNO board.

## Usage
### 1. Login:

* Power on the EVM.
* The Oled display will prompt you to enter the login password.
* Enter the password to proceed.
  
### 2. Main Menu:

* After successful login, the EVM will display two options:
  1. Voting mode.
  2. Results.
* Vote for your preferred option by pressing the corresponding pushbutton
  
### 3. Voting:

* If you choose option 1 (Voting), enter your Voter ID when prompted.
* The Oled display will show a list of three candidates
   1. Virat.
   2. Dhoni.
   3. Sachin.
* Vote for your preferred candidate by pressing the corresponding push button.
* The system will confirm your vote with a message like "Casted to [Person]."
* You can then vote again or move to the Results option.

### 4. Results:

* If you choose option 2 (Results), enter your login password again for verification.
* The Oled display will then show the total votes cast for each candidate.
* It will also announce the winner based on the candidate with the maximum votes.

## Notes

* Ensure that all connections are secure before powering on the EVM.
* The provided code (evm.ino) contains the necessary logic for the described functionality.
* Feel free to modify the code to suit your requirements or enhance the features.
  
Happy Voting!
