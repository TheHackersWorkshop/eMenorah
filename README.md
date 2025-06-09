# eMenorah

### YouTube video
https://www.youtube.com/watch?v=8hWp5Kh7FtA

Overview
This repository contains all the design files and documentation for the Electronic Menorah project, an innovative approach to creating a menorah that uses RGB LEDs to simulate candle flames. The design is based on a combination of logic chips and microcontrollers to create flickering effects that mimic real flames.

Features
RGB LED Flickering: Utilizes RGB LEDs to create a realistic flickering flame effect.
Schmitt Trigger Oscillators: Uses CD40106 Schmitt Trigger for generating independent flickering effects for each LED.
Logic Control: Employs 74HC00N quad NAND gates for controlling the state of each LED.
Touch Sensitivity: Incorporates a TTP223 capacitive touch sensor to advance the lighting of each candle.
Safety Features: Design includes measures to prevent overheating and electrical faults.
Components
RGB LEDs: Provide the visual flame effects.
CD40106 Schmitt Trigger: Generates the flickering frequency for each LED.
74HC00N NAND Gate: Manages the LED states based on the counter's output.
CD4017 Decade Counter: Controls the sequence of LED activation.
TTP223 Touch Sensor: Allows user interaction for advancing the candle lighting.
Resistors and Capacitors: Sized to control the timing and intensity of the LED flickering.
Circuit Description
The Electronic Menorah's circuit includes several key components arranged to ensure efficient operation and user safety:

Control Setup
TTP223 Touch Sensor is connected to VCC and GND, with the output going to Pin 14 of the CD4017 Decade Counter to advance the lighting sequence upon each touch.
CD40106 Schmitt Triggers are configured with specific resistor-capacitor pairs to create distinct flickering effects for each set of LEDs. This configuration helps simulate the natural variation in flame flickering.
LED Control
Each LED is connected to a 74HC00N NAND gate that controls its state based on the output from the CD4017. This setup allows for precise control over each "candle" in the menorah, ensuring they light up in sequence and with the desired effect.

# eMenorah
Electronic Menorah Project
