# LED Blinking using Arduino

This project demonstrates a basic embedded systems program that controls an LED connected to an Arduino board. The LED is programmed to continuously blink with a delay of one second. This simple experiment helps beginners understand digital output and microcontroller programming using Arduino.

## Project Overview

- Learn how to configure Arduino digital pins  
- Control external hardware (LED) using simple code  
- Understand delay, digital write operations, and looping  
- Practice using GitHub for code management and QA tracking  

## Hardware Requirements

- Arduino Uno / Mega / Nano  
- Built-in LED on Pin 13 or external LED  
- Resistor (220Ω) if using external LED  
- Arduino IDE  
- USB cable  

## Circuit Diagram (Simple Explanation)

If using external LED:

LED (+) → Pin 13  
LED (−) → 220Ω Resistor → GND

If using built-in LED, no wiring is needed.

## Code Explanation

The code:
1. Sets pin 13 as an OUTPUT  
2. Turns the LED ON for 1 second  
3. Turns the LED OFF for 1 second  
4. Repeats forever  

## Arduino Code

```cpp
const int ledPin = 13;  // Built-in LED on most Arduino boards

void setup() {
  pinMode(ledPin, OUTPUT);
}

void loop() {
  digitalWrite(ledPin, HIGH);  // Turn LED on
  delay(1000);                 // Wait 1 second
  digitalWrite(ledPin, LOW);   // Turn LED off
  delay(1000);                 // Wait 1 second
}
```

## QA Improvements Suggested

- Remove duplicate setup() and loop() functions  
- Add proper comments to Arduino code  
- Add circuit explanation  
- Improve README formatting  
- Add descriptive commit messages  

All improvements are tracked through GitHub Issues.

## Collaboration

Issues were created, commented on, and resolved using the GitHub Issues section.  
Each issue was reviewed and closed after verification of the fix.

## Learning Outcomes

- Understanding of basic GitHub repository management  
- Practical experience in logging QA issues  
- Improved documentation and embedded coding skills  
- Exposure to collaboration workflow in software projects  
- Enhanced understanding of Arduino digital I/O  

# Student Information

**Name:** Omkar Varote  
**PRN:** 202201070136  
**Division:** B  
**Subject:** Project Management  
