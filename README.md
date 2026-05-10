# RGB LED and 3 Single LEDs Control

This project demonstrates how to control an **RGB LED** along with **3 individual LEDs** using a microcontroller/Arduino.

It allows users to switch ON/OFF individual LEDs and mix RGB colors through programming logic.

---

## 📌 Features

- Control **Red, Green, Blue** channels of RGB LED.
- Control **3 Separate Single LEDs**.
- Generate multiple colors using RGB combinations.
- Simple digital output-based LED control.
- Beginner-friendly embedded systems project.

---

## 🛠️ Components Used

- Arduino Uno / Compatible Microcontroller.
- 1 RGB LED.
- 3 Single LEDs.
- Resistors (220Ω / 330Ω)
- Breadboard.
- Jumper Wires.
- USB Cable / Power Supply.

---

## 🔌 Circuit Connections

### RGB LED Pins

- Red Pin    → Digital Pin 9
- Green Pin  → Digital Pin 10
- Blue Pin   → Digital Pin 11

### Single LEDs

- LED 1 → Digital Pin 2
- LED 2 → Digital Pin 3
- LED 3 → Digital Pin 4

> **Note:** Use current-limiting resistors for all LEDs.

---

## 💻 Arduino Code

cpp

int red = 9;

int green = 10;

int blue = 11;

int led1 = 2;

int led2 = 3;

int led3 = 4;

void setup() 

{

  pinMode(red, OUTPUT);
  
  pinMode(green, OUTPUT);
  
  pinMode(blue, OUTPUT);

  pinMode(led1, OUTPUT);
  
  pinMode(led2, OUTPUT);
  
  pinMode(led3, OUTPUT);
  
}

void loop()

{

  // RGB LED Colors
  
  digitalWrite(red, HIGH);
  
  delay(500);
  
  digitalWrite(red, LOW);

  digitalWrite(green, HIGH);
  
  delay(500);
  
  digitalWrite(green, LOW);

  digitalWrite(blue, HIGH);
  
  delay(500);
  
  digitalWrite(blue, LOW);

  // Single LEDs
  
  digitalWrite(led1, HIGH);
  
  digitalWrite(led2, HIGH);
  
  digitalWrite(led3, HIGH);
  
  delay(1000);

  digitalWrite(led1, LOW);
  
  digitalWrite(led2, LOW);
  
  digitalWrite(led3, LOW);
  
  delay(1000);
  
}

---

# 👨‍💻 Author

**Madhan Kumar**

- GitHub    : [https://github.com/Madhan-03] 
- LinkedIn  : [https://www.linkedin.com/in/madhan-kumar-128644362/]   

---
