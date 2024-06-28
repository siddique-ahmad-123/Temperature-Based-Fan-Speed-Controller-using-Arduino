# Temperature Based Fan Speed Controller using Arduino

This project implements a temperature-based fan speed controller using an Arduino Uno. The system adjusts the fan speed based on the ambient temperature, providing efficient cooling and energy management.

## Circuit Diagram

![Circuit Diagram](circuit_diagram_url.jpg)

## Components Used

- Arduino Uno
- LM35 Temperature Sensor
- 16x2 LCD Display
- DC Fan (12V)
- 2N2222 NPN Transistor
- LED (for status indication)
- Resistors: 1K ohm (x2)
- Capacitor: 10 μF
- 12V Power Supply

## Circuit Explanation

1. **Temperature Sensing**: The LM35 temperature sensor is connected to the Arduino's analog input. It provides accurate temperature readings.

2. **Fan Control**: The DC fan is controlled using PWM through the 2N2222 transistor. The transistor acts as a switch, allowing the Arduino to control the fan speed.

3. **Display**: A 16x2 LCD display is used to show the current temperature and fan speed.

4. **Status Indication**: An LED is included to indicate the system's operational status.

5. **Power Supply**: A 12V power supply powers both the Arduino and the fan. The Arduino's onboard regulator provides the necessary 5V for the other components.

## How It Works

1. The LM35 sensor continuously measures the ambient temperature.
2. The Arduino reads this temperature value through its analog input.
3. Based on predefined temperature thresholds, the Arduino adjusts the fan speed using PWM.
4. The current temperature and fan speed are displayed on the LCD.
5. The LED provides a visual indication of the system's operation.

## Installation and Setup

1. Connect the components as shown in the circuit diagram.
2. Upload the provided Arduino sketch to your Arduino Uno.
3. Power on the system using a 12V power supply.

## Usage

Once powered on, the system will automatically start monitoring the temperature and adjusting the fan speed accordingly. The LCD will display the current temperature and fan speed percentage.

## Customization

You can modify the temperature thresholds and corresponding fan speeds in the Arduino code to suit your specific requirements.

## Contributing

Contributions to improve this project are welcome. Please feel free to fork the repository and submit pull requests.
