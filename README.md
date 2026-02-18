This project demonstrates basic GPIO control using the gpiozero library in Python.

The LED connected to GPIO pin 17 blinks continuously:

🔴 ON for 1 second

⚫ OFF for 1 second

This is a beginner-friendly project for learning Raspberry Pi hardware interfacing.

🛠 Hardware Requirements

🖥 Raspberry Pi

🔴 LED

🔌 Resistor (220Ω recommended)

🔗 Jumper wires

🍞 Breadboard (optional)

🔌 Circuit Connection
Component	Raspberry Pi GPIO
LED (+)	GPIO 17
LED (–)	GND (through resistor)
💻 Software Requirements

Python 3

gpiozero library

Install gpiozero (if not already installed):

pip install gpiozero

▶️ How to Run

Connect the LED as shown above.

Save the file as led.py

Run the program:

python led.py


The LED will start blinking continuously.

📂 Project Structure
led.py
README.md
