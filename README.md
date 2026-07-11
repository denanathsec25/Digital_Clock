# ⏰ Digital Clock

A 24-hour digital clock designed using **NE555 Timer**, **CD4026 Decade Counter ICs**, combinational reset logic, and **6 Common Cathode 7-Segment Displays**. The project was implemented on a breadboard and documented with complete block diagrams, schematics, and project reports.

---

## Features

- 24-Hour Time Format (00–23)
- Optional Day Counter (00–06)
- 1 Hz Clock Generation using NE555
- CD4026-Based Counter Design
- Automatic Reset Logic
- 6 Common Cathode 7-Segment Displays
- Modular Hardware Design
- Breadboard Prototype

---

## Components Used

- NE555 Timer
- CD4026 Decade Counter ICs
- Common Cathode 7-Segment Displays
- Logic Gates
- 220 Ω Resistors
- Capacitors
- Breadboard
- Jumper Wires
- 5V Power Supply

---

## Working Principle

- NE555 generates a stable **1 Hz clock**.
- Seconds count from **00–59**.
- Minutes count from **00–59**.
- Hours count from **00–23**.
- (Optional) Day counter increments after every 24-hour cycle.
- Reset logic automatically resets each counter at its maximum count.

---

## Project Structure

```
Digital Clock
├── Block Diagrams
│   ├── Version 1
│   └── Version 2
├── Schematics
├── Documentation
├── Datasheets
└── Images
```

---

## Challenges Faced

- **Incorrect 60-count reset:** The counters occasionally failed to reset correctly at 60.
- **Reset signal instability:** False triggering occurred due to noisy reset signals.
- **Counter synchronization:** Cascading multiple CD4026 ICs required proper carry propagation.
- **Module integration:** Integrating seconds, minutes, hours, and day counters together was challenging during testing.

### Solution

- Added **220 Ω resistors** in the reset logic to stabilize the reset signals.
- Designed and verified **each module (seconds, minutes, hours, and day counter) independently** before integrating them into the complete system.
- Tested the reset logic separately to ensure accurate transitions at **60 seconds**, **60 minutes**, and **24 hours**.

---

## Future Improvements

- PCB Implementation
- Time Setting Buttons
- RTC (DS3231) Integration
- Alarm Function
- Date & Calendar Display
- FPGA/Verilog Implementation

---

## Contributors

- **Denanath Shanmugasundaram**
- **Team Members**

---

⭐ If you found this project useful, consider giving it a star!
