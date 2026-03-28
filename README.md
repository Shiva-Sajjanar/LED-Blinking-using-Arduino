# 🔵 LED Blinking using Arduino

## 📌 Project Overview

This project demonstrates a simple LED blinking program using an Arduino board. It is one of the most basic and beginner-friendly embedded systems projects, useful for understanding digital output and timing control.

---

## 🛠️ Components Required

* Arduino Board (UNO / Nano / Mega)
* LED
* 220Ω Resistor
* Breadboard
* Jumper Wires

---

## 🔌 Circuit Diagram

* Connect the **LED positive (long leg)** to **digital pin 13**
* Connect the **LED negative (short leg)** to **GND through a resistor**

---

## 💻 Code

```cpp
void setup() {
  pinMode(13, OUTPUT); // Set pin 13 as output
}

void loop() {
  digitalWrite(13, HIGH); // Turn LED ON
  delay(1000);            // Wait for 1 second
  digitalWrite(13, LOW);  // Turn LED OFF
  delay(1000);            // Wait for 1 second
}
```

---

## ▶️ How It Works

* The Arduino sends HIGH signal to pin 13 → LED turns ON
* Waits for 1 second
* Sends LOW signal → LED turns OFF
* This process repeats continuously, creating a blinking effect

---

## 🚀 Features

* Simple and beginner-friendly project
* Demonstrates basic Arduino programming
* Helps understand digital output and delay timing

---

## 📈 Future Improvements

* Control LED using a push button
* Change blinking speed dynamically
* Use multiple LEDs (pattern blinking)
* Control LED using sensors (LDR, IR, etc.)

---

## 🎥 Demo (Optional)

Add a video or GIF here to show the working project.

---

## 📚 Learning Outcomes

* Basics of embedded C programming
* Understanding Arduino pin configuration
* Hands-on hardware interfacing

---

## 🤝 Contributing

Feel free to fork this repository and improve the project!

---

## 📄 License

This project is open-source and free to use.
