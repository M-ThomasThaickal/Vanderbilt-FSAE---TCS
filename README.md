# Vanderbilt FSAE — Traction Control System (TCS)

## Overview
This repository documents the research, design, and implementation of a traction control system (TCS) for Vanderbilt’s Formula SAE combustion car.  
The current ECU, **PE3 8400**, does include built-in TCS support, so the goal is to enable its feature in the ecu and tune to best meet our needs.

The documentation here is intended for:
- Current team members working on the car
- Future FSAE members inheriting this project
- Documenting progress

## Why This Project Matters
Traction control is a vehicle dynamics control system that prevents wheel slip during acceleration, improving lap times and vehicle stability. This project combines:
- **Embedded systems** (sensor integration, real-time processing)
- **Control theory** (slip detection and intervention algorithms)  
- **Hardware-software integration** (ECU communication protocols)
- **Real-world validation** (testing and tuning on actual race car)

---

## Roadmap
- **Completed**  
  Gather background on traction control, confirm legality in FSAE rules, and study ECU documentation. 
  Determine if Pi is needed, write code for wheel speed sensing
  Arduino prototype with hall effect sensors
  Validation with manual lathe
  Migration to Raspberry Pi
  4-channel independent wheel speed monitoring
  Wiring
- **In Progess**
  Physical mounting and installation
  ECU integration
  System tuning/testing
- **For future**
  Live-testing
  Data logging/live analysis
  TCS tuning
---

## Repository Structure
```
fsae-tcs/
│── README.md # Project overview
│── docs/
│ ├── research.md # Notes from papers, videos, rulebook
│ ├── ecu.md # PE3 8400 details, configs, limitations
├── src/
└── data/ # Log files, CSVs, test results, code
```