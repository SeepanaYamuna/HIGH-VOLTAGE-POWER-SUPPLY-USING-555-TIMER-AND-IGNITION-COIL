# HIGH-VOLTAGE-POWER-SUPPLY-USING-555-TIMER-AND-IGNITION-COIL
High-voltage power supply using a 555 timer oscillator and ignition coil. Converts low DC input into high voltage through high-frequency switching and inductive energy transfer. Demonstrates practical power electronics, oscillator design, and real-world high-voltage generation.

## OVERVIEW

This project demonstrates the design and implementation of a high-voltage power supply using a 555 timer-based oscillator and an automotive ignition coil. The system converts low DC voltage into high-voltage output using high-frequency switching techniques.

---

## WORKING PRINCIPLE

The circuit is based on a high-frequency oscillator driving a power transistor, which in turn excites an ignition coil acting as a step-up transformer.

* 555 Timer configured in **astable mode**
* Generates high-frequency square wave
* Transistor acts as a switching amplifier
* Ignition coil steps up voltage to high levels

High voltage generation is achieved through rapid switching of current in an inductive element, a principle similar to switching converters. ([Creative Engineering][1])

---

## CIRCUIT DESCRIPTION

* Oscillator Supply: 9V
* Power Stage Supply: 24V (SMPS)
* Adjustable frequency using potentiometer
* Separate supply used to protect control circuitry from inductive spikes

The ignition coil behaves as a high-voltage transformer and produces large voltage spikes due to inductive switching. ([Creative Engineering][1])

---

## IMPLEMENTATION

The circuit was implemented using:

* NE555 Timer IC
* NPN Power Transistor
* Automotive Ignition Coil
* Dual power supply configuration

---

## SAFETY NOTE

* High voltage output can be **dangerous**
* Proper insulation and handling required
* Avoid direct contact with output terminals

---

## KEY OBSERVATIONS

* Output voltage depends on switching frequency
* Maximum output achieved at resonance tuning
* Inductive kickback generates high voltage spikes

---

## APPLICATIONS

* Plasma generation
* High-voltage experiments
* Ignition systems
* Educational demonstrations

---

## FUTURE IMPROVEMENTS

* Add feedback regulation for voltage control
* Implement protection circuits
* Replace discrete setup with PCB design

---

## KEY TAKEAWAY

This project highlights how low-voltage DC can be efficiently converted into high voltage using switching techniques, oscillators, and inductive energy transfer — a fundamental concept in power electronics and RF systems.


