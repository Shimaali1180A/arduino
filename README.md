🔴🟡🟢 Arduino Project: 3 Buttons Control 3 LEDs

This beginner-friendly Arduino project demonstrates how to control three individual LEDs using three pushbuttons. Each button is linked to one LED — when you press the button, the corresponding LED lights up.

🔌 Components Required
 • 1 × Arduino Uno
 • 3 × Pushbuttons
 • 3 × LEDs (any color)
 • 3 × 220Ω resistors (for the LEDs)
 • 3 × 10kΩ resistors (for the pushbuttons)
 • 1 × Breadboard
 • Jumper wires

🧠 How It Works

Each pushbutton is connected to one of the Arduino’s digital input pins and grounded through a 10kΩ pull-down resistor. This ensures the pin reads LOW when the button is not pressed.

When a button is pressed, the corresponding input pin reads HIGH. The Arduino then turns on the LED connected to the matching output pin.

🛠 Circuit Connections
 • Button 1 → Digital pin 2
 • Button 2 → Digital pin 3
 • Button 3 → Digital pin 4
 • LED 1 → Digital pin 10
 • LED 2 → Digital pin 11
 • LED 3 → Digital pin 12

Each LED is connected in series with a 220Ω resistor to limit the current. Each pushbutton uses a 10kΩ resistor as a pull-down to ground.

🔁 Behavior
 • Press Button 1 → LED 1 turns ON
 • Press Button 2 → LED 2 turns ON
 • Press Button 3 → LED 3 turns ON

Once the button is released, the LED turns off again.

📷 Output

When wired correctly, pressing each button will light up its corresponding LED. This provides a simple demonstration of digital input/output interaction on the Arduino.
