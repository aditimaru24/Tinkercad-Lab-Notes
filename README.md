# My Embedded Systems Logbook 🚀

Welcome to my repository tracking my growth in firmware development and circuit design. 

## Projects Index
* [Project 1: Basic LED Blink](#project-1-basic-led-blink)
* [Project 2: Traffic Light Simulator](#project-2-traffic-light-simulator)

---

## Project 1: Basic LED Blink
**Description:** My very first circuit controlling physical hardware parameters. Learned about GPIO configuration and simple time delays.
* **Tools Used:** Tinkercad, Arduino C++
* **Circuit Diagram:** file:///C:/Users/aditi/OneDrive/Pictures/Screenshots/Screenshot%202026-06-18%20160531.png
  ### Code
```cpp
void setup() {
  pinMode(13, OUTPUT);
}
void loop() {
  digitalWrite(13, HIGH);
  delay(100);
  digitalWrite(13, LOW);
  delay(100);
}
