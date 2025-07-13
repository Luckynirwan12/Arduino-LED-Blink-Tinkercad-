# 💡 Arduino LED Blink Project
## 📌 Overview
This project demonstrates how to use an Arduino Uno to control an LED, making it blink at regular intervals. It's a foundational experiment for learning how to control digital outputs using Arduino code.

## 🧰 Components Used
- Arduino Uno

- Breadboard

- 1x LED (Red)

- 1x 220Ω resistor (to limit current and protect the LED)

- Jumper wires

## 🔌 Circuit Explanation
- The long leg (anode) of the LED is connected to digital pin 13 of the Arduino via a jumper wire.

- The short leg (cathode) is connected to GND through a 220Ω resistor.

- This setup completes the circuit and allows the LED to be powered and controlled by the Arduino.

## 🧠 Working Principle
- The Arduino sketch (code) sends a HIGH signal to pin 13 for a short period (e.g., 1 second), lighting up the LED.

- Then it sends a LOW signal, turning the LED off.

- This cycle repeats to create a blinking effect.

## 💡 Arduino Code
The Arduino sketch for this project is saved in the file:

📂 `Arduino_LED_Blink.ino`
  
## 📸 Demonstration Snapshot:
<img width="1656" height="715" alt="image" src="https://github.com/user-attachments/assets/93344fde-6adc-4776-bd78-bd3db943705b" />
