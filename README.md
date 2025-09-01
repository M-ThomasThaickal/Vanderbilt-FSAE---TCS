# Vanderbilt FSAE — Traction Control System (TCS)

## Overview
This repository documents the research, design, and implementation of a traction control system (TCS) for Vanderbilt’s Formula SAE combustion car.  
The current ECU, **PE3 8400**, does not include built-in TCS support, so the goal is to design a custom solution that integrates wheel speed sensors, slip ratio calculations, and torque modulation strategies.

The documentation here is intended for:
- Current team members working on the car
- Future FSAE members inheriting this project
- Technical reference for control algorithms and software

---

## Project Goals
1. **Understand TCS fundamentals** — slip ratio, wheel speed sensing, torque reduction methods.
2. **Evaluate hardware capabilities** of the PE3 8400 ECU and determine integration options.
3. **Develop algorithms** for slip detection and real-time control (starting simple, then refining).
4. **Implement a working system** on the car with safe and testable stages.
5. **Document the process** so future members can continue development.

---

## Roadmap
- **Phase 1 — Research & Rules**  
  Gather background on traction control, confirm legality in FSAE rules, and study ECU documentation.

---

## Repository Structure

fsae-tcs/
│── README.md # Project overview
│── docs/
│ ├── research.md # Notes from papers, videos, rulebook
│ ├── ecu.md # PE3 8400 details, configs, limitations
│── src/ # Code 
│── data/ # Log files, CSVs, test results