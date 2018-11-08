# Pulse-Sensor
## Description

Pulse Sensor Amped is a plug-and-play heart-rate sensor for Arduino and Arduino compatibles. It can be used to easily incorporate live heart-rate data into their projects. Pulse Sensor adds amplification and noise cancellation circuitry to the hardware. It's noticeably faster and easier to get reliable pulse readings. Pulse Sensor Amped works with either a 3V or 5V Arduino

## Specification

- Diameter = 0.625" (~16mm)  
- Overall thickness = 0.125" (~3mm)  
- Working Voltage = 3V to 5V  
- Working Current = ~4mA at 5V  

## Step 1: Material Preparation
1. Arduino Uno Board and USB Cable.
2. Pulse Sensor Arduino
3. Jumper Wires
4. Breadboard
## Step 2: PIN Connection
1. s to analog pin 0 
2. '+' supply 3V uptp 5V 
3. '-' to ground 
## Step 3: Add pulseSensor libraray to you sketch
Sketch -> include library -> manage libraries -> search for PulseSensor and install it.

###### An example code for displaying BPM to serial monitor is uploaded
