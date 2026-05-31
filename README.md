# DC-VARIABLE-POWER-SUPPLY

## Overview

This project focuses on the design and implementation of a Variable DC Power Supply capable of providing an adjustable and regulated DC output for electronics testing and prototyping applications.

The circuit was initially developed and tested on a breadboard before being transferred to a perfboard for a more compact, reliable, and permanent implementation. Additional protection features such as a fuse, power switch, and reverse polarity protection were incorporated to improve safety and usability.

---

## Features

* Adjustable DC Output Voltage
* Step-Down Transformer-Based Design
* Bridge Rectifier for AC to DC Conversion
* Filter Capacitors for Ripple Reduction
* Voltage Regulation Circuit
* Reverse Polarity Protection
* Fuse Protection
* Power ON/OFF Switch
* Perfboard Implementation

---

## Components Used

* Step-Down Transformer
* Bridge Rectifier
* Filter Capacitors
* Voltage Regulator Circuit
* Potentiometer
* Fuse
* Power Switch
* Protection Diode (Reverse Polarity Protection)
* Perfboard
* Connecting Wires and Terminals

---

## Working Principle

The AC mains voltage is first stepped down to a lower AC voltage using a transformer. This AC voltage is then converted into DC using a bridge rectifier. The rectified output is filtered using capacitors to reduce ripple and obtain a smoother DC voltage.

The voltage regulation stage provides an adjustable and stable output voltage suitable for powering electronic circuits. A fuse is placed at the input side for protection against excessive current conditions, while a power switch allows safe operation of the supply.

To prevent accidental damage caused by incorrect output polarity connections, a reverse polarity protection circuit has also been incorporated into the design.

---

## Development Process

1. Designed and tested the circuit on a breadboard.
2. Verified voltage regulation and output stability.
3. Added reverse polarity protection, fuse, and power switch.
4. Transferred the complete circuit to a perfboard.
5. Performed testing and troubleshooting.
6. Achieved a stable and functional variable DC power supply.

---

## Applications

* Electronics Prototyping
* Embedded Systems Development
* Arduino and ESP32 Projects
* Sensor Testing
* Educational Laboratories
* General Purpose Bench Power Supply

---

## Future Improvements

* Digital Voltmeter Display
* Digital Ammeter Display
* Current Limiting Protection
* USB Output Ports
* Custom PCB Design
* Enclosure Design

---

## Author

Tirth Kushwaha

Electronics & Telecommunication Engineering
Embedded Systems | IoT | Robotics | PCB Design
