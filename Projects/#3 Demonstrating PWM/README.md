# ⚡ Demonstrating PWM — Arduino

> **Don't just switch it ON. Command its intensity. Master the signal.**

## 🧠 Project Overview

**Demonstrating PWM** is an Arduino-based electronics project that explores how digital signals can achieve variable output control through **Pulse-Width Modulation (PWM)**.

Using an **Arduino UNO**, the project controls an LED's brightness by dynamically adjusting its PWM duty cycle. The program gradually increases the brightness from minimum to maximum, then reverses the sequence until the LED returns to darkness.

Although the circuit is simple, it introduces a powerful engineering principle:

> **Precise output control through software-defined signals.**

This project is part of my journey toward building **Stark-level intelligent hardware and automation systems**.

---

## 🎯 Objective

The objective of this project is to understand how an Arduino can:

- Generate PWM signals using `analogWrite()`
- Control LED brightness through duty-cycle adjustments
- Simulate variable output using digital signals
- Implement gradual changes using `for` loops
- Control output timing through programmed delays
- Transform simple code into dynamic hardware behavior

---
## 🔗 Live Simulation
Test, tweak, and run the simulation live in your browser:
👉 [Open LED Blinking Wave in Tinkercad Circuits](https://www.tinkercad.com/things/9k5OTU20CYx-demonstrating-pwm)


## ⚙️ Working Principle

Instead of keeping the LED permanently ON or OFF, the Arduino rapidly switches its output between HIGH and LOW.

By changing the proportion of time the signal remains HIGH, the program controls the LED's perceived brightness.

```text
LOW DUTY CYCLE  →  DIM LIGHT
       ↓
INCREASING PWM →  BRIGHTER LIGHT
       ↓
HIGH DUTY CYCLE →  MAXIMUM BRIGHTNESS
       ↓
DECREASING PWM →  DIMMER LIGHT
       ↓
ZERO DUTY CYCLE →  DARKNESS


