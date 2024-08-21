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
![IMG_20231109_171302_354](https://github.com/user-attachments/assets/ac6a4cd6-5577-4af7-8136-816e7b4f1e86)

## Usage

### 1. Login
- Power on the EVM.
- Enter the login password displayed on the Oled to proceed
![IMG_20231109_172248_251](https://github.com/user-attachments/assets/717eaad6-299e-461e-bc7e-085a1408d088)



### 2. Main Menu
- Choose between **Voting** and **Results** using the pushbuttons.
  ![IMG_20231109_171710_160](https://github.com/user-attachments/assets/d8fe9318-2d08-4000-8540-6a09ad89b9e7)


### 3. Voting
- Select **Voting** and enter your Voter ID.
- Choose your candidate (Virat, Dhoni, Sachin) by pressing the corresponding pushbutton.
- A confirmation message will appear, and you can vote again or view results.
![IMG_20231109_172722_683](https://github.com/user-attachments/assets/58101ae5-86e3-4914-b806-48b70273cb0a)


### 4. Results
- Select **Results** and re-enter the login password.
- The display will show the total votes and announce the winner.
![IMG_20231109_173426](https://github.com/user-attachments/assets/a2013636-d079-4d2c-9282-fc26936ec749)

## Notes
- Ensure secure connections before powering on.
- The code (evm.ino) contains all necessary logic and can be modified as needed.

Happy Voting!
