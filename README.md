# Anti-Epilepsy-Glasses-Prototype
Overview

This project is an analog smart glasses prototype designed to protect users from sudden high-intensity light exposure, which can trigger photosensitive epilepsy.

The system detects light intensity using an LDR (Light Dependent Resistor) and automatically darkens LCD shutters placed in front of the eyes.

---

Working Principle

- LDR senses ambient light intensity
- Signal is processed using an analog voltage divider
- MOSFET acts as a switch
- LCD shutters darken when high light is detected
- Capacitor smooths response (reduces flicker)
- Diode enables fast activation and controlled recovery

---

Components Used

- LDR (Light Dependent Resistor)
- IRLZ44N MOSFET
- LCD Shutter (2 units)
- 3.7V LiPo Battery
- Charging Module (TP4056 / MCP73831)
- Resistors (10k, 220k / Potentiometer)
- Capacitor (10µF)
- Diode (1N4148 / 1N4007)
- Slide Switch

---

Circuit Description

The LDR forms a voltage divider with a resistor/potentiometer.
The output controls the MOSFET gate.
When light intensity exceeds a threshold:
→ MOSFET turns ON
→ LCD shutters darken

---

Setup Instructions

1. Connect battery through switch to power rails
2. Connect LCD shutters in parallel
3. Connect MOSFET as low-side switch
4. Build LDR voltage divider
5. Add capacitor for smoothing
6. Add diode for fast ON response
7. Tune sensitivity using potentiometer

---

Demo Video

https://drive.google.com/drive/folders/1YgEPt7TDjtV-NXDReF13e_zjiZ9X6KaY

---

Point of Contact

Name: K.Bodhin Manas
Email: kukunoori.bodhin@gmail.com

---

🚀 Future Improvements

- Frequency-based flicker detection
- Microcontroller integration
- Compact PCB design
- Real-time adaptive filtering
- ML Integration using microcontroller
---
