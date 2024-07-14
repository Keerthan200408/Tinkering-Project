This Arduino project controls a fan's speed based on temperature readings from a DHT22 sensor and commands received from an IR remote. The system includes different user profiles and a manual control mode to adjust the fan speed.

**Components**:
Arduino Uno
DHT22 Temperature and Humidity Sensor
16x2 LCD Display
IR Receiver Module
Fan (DC Motor)
Transistor
Resistors
IR Remote
Jumper wires
Breadboard
**How It Works**:-
**Setup**: The system initializes the DHT22 sensor, LCD display, and IR receiver.
Temperature Reading: The DHT22 sensor continuously measures the temperature and humidity.
**Display**: The measured temperature is displayed on the 16x2 LCD.
**IR Control**: The IR receiver captures signals from the remote to switch between different user profiles or manual control mode.
User Profiles:
**Profile 1**: Adjusts fan speed based on specific temperature thresholds for user 1.
**Profile 2**: Adjusts fan speed based on specific temperature thresholds for user 2.
**General Profile**: Adjusts fan speed for general use.
**Manual Profile**: Allows manual adjustment of the fan speed using a potentiometer.
**Fan Control**: The fan speed is controlled by a PWM signal sent to a transistor, which adjusts the power supplied to the fan based on the selected profile or manual setting.
Usage
Connect the components as per the circuit diagram.
Upload the provided code to your Arduino.
Use the IR remote to switch between different profiles or manually control the fan speed.
Observe the temperature and fan speed on the LCD display.
