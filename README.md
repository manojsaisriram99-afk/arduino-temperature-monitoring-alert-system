Arduino Temperature Monitoring System

Overview :-

This project implements a temperature monitoring and alert system using Arduino.
The system measures ambient temperature using a TMP36 temperature sensor, displays the temperature on a 16×2 LCD display, and activates a buzzer when the temperature exceeds a predefined threshold.

Components Used:-

Arduino Uno

TMP36 Temperature Sensor

16×2 LCD Display

Piezo Buzzer

10kΩ Potentiometer

220Ω Resistor

Breadboard

Jumper Wires

Circuit Connections:-

• TMP36 Temperature Sensor

VCC → 5V

VOUT → A0

GND → GND

• LCD Display

RS → Arduino Pin 7

E → Arduino Pin 6

D4 → Arduino Pin 5

D5 → Arduino Pin 4

D6 → Arduino Pin 3

D7 → Arduino Pin 2

VSS → GND

VDD → 5V

VO → Potentiometer middle pin

RW → GND

LED+ → 5V through 220Ω resistor

LED− → GND

• Potentiometer

Terminal 1 → GND

Terminal 2 → LCD Pin 3 (VO)

Terminal 3 → 5V

• Buzzer

Positive → Arduino Pin 8

Negative → GND

Working Principle:-

• The TMP36 temperature sensor produces an analog voltage proportional to the surrounding temperature.

• The Arduino reads this analog signal through an analog input pin and converts it into temperature in degrees Celsius.

• The measured temperature is displayed on the LCD screen. If the temperature exceeds the defined threshold (for example 35°C), the buzzer is activated to provide an alert.

Applications:-

• Temperature monitoring systems

• Environmental monitoring

• Embedded systems learning

• Basic sensor interfacing projects

Future Improvements:-

Add a cooling fan using a relay module

Integrate IoT monitoring using Wi-Fi modules

Store temperature data for analysis

Author

Manoj Sai Sriram

Electronics and Communication Engineering
