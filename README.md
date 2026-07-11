# ⏰ Digital Clock using CD4026 and NE555

A 24-hour digital clock built using the **NE555 Timer**, **CD4026 Decade Counter/7-Segment Driver**, logic gates, and seven-segment displays. The project was designed, simulated, and implemented on a breadboard with custom reset logic for seconds, minutes, hours, and day counting.

---

## 📌 Features

- 24-Hour Digital Clock
- Seconds (00–59)
- Minutes (00–59)
- Hours (00–23)
- Day Counter
- Automatic Reset Logic
- Breadboard Implementation
- Altium Schematic Design
- Two Versions of Reset Logic (V1 & V2)

---

## 📂 Repository Structure

```text
Digital_Clock/
│
├── Circuit/
│   └── Digital Clock Schematic/
│       ├── Digital Clock Schematic V1,V2.pdf
│       └── Block Diagram V1,V2.pdf
│
├── Images/
│   ├── Block Diagram V1.png
│   ├── Block Diagram V2.png
│   ├── Breadboard Setup.jpg        (Optional)
│   ├── Final Output.jpg            (Optional)
│   └── Circuit Diagram.png         (Optional)
│
├── ChronoBit26_Report.pdf
│
└── README.md
```
---

## 🛠 Components Used

- NE555 Timer IC
- CD4026 Decade Counter
- 7-Segment Displays
- Logic Gates (AND, NOT)
- Resistors
- Capacitors
- Breadboard
- Jumper Wires
- 5V Power Supply

---

## 📖 Project Description

The NE555 timer is configured as an astable multivibrator to generate the clock pulse. The CD4026 ICs count the pulses and directly drive the seven-segment displays.

Custom combinational reset logic is implemented to achieve:

- Seconds : 00–59
- Minutes : 00–59
- Hours : 00–23
- Day Counter Increment

Two versions of the reset logic were designed and compared.

---

## ⚠ Challenges Faced

- Designing reliable reset logic for the hour counter.
- Ensuring proper transition from **23 → 00**.
- Preventing incorrect counts during reset.
- Debugging timing issues in the NE555 clock pulse.
- Testing each module independently before integration.

---

## 📄 Documentation

- Project Report
- Circuit Schematics
- Block Diagrams
- Breadboard Implementation

---

## 👥 Contributors

- [@denanathsec25](https://github.com/denanathsec25)
- [@prateeksha23-bs](https://github.com/prateeksha23-bs)
- [@tejaswiniss399](https://github.com/tejaswiniss399)

---

## ⭐ If you found this project useful, consider giving the repository a Star.
