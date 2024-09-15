# Election Voting System

This project uses an Arduino, OLED display, and buttons to create a simple election voting system. It supports password-protected voting and results display.

## Components

- Arduino (e.g., Arduino Uno)
- OLED Display (SSD1306)
- Push Buttons (3)
- Wires

## Wiring

- **OLED Display:**
  - `SCL` -> Arduino `A5`
  - `SDA` -> Arduino `A4`
  - `VCC` -> Arduino `5V`
  - `GND` -> Arduino `GND`
  
- **Buttons:**
  - Button 1 -> Arduino `pin 2`
  - Button 2 -> Arduino `pin 3`
  - Button 3 -> Arduino `pin 4`

## Functionality

1. **Password Entry:** Enter a password via Serial Monitor to access voting or results.
2. **Voting:** Cast votes for Virat Kohli, Sachin Tendulkar, or MS Dhoni using the buttons.
3. **Results:** View vote counts and the winner on the OLED display.
4. **Identity Verification:** Ensure each voter can vote only once.

## Usage

1. **Upload Code:** Load the Arduino sketch onto your board.
2. **Connect Components:** Wire the OLED display and buttons.
3. **Power Up:** Connect the Arduino to a power source.
4. **Interact:** Use the Serial Monitor for password entry and buttons for voting.

## Troubleshooting

- **Display Issues:** Check connections and I2C address.
- **Button Issues:** Verify button wiring and responsiveness.
