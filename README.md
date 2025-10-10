# Vanderbilt FSAE — Traction Control System (TCS)

## Overview
This repository documents the research, design, and implementation of a traction control system (TCS) for Vanderbilt’s Formula SAE combustion car.  
The current ECU, **PE3 8400**, does include built-in TCS support, so the goal is to enable its feature in the ecu and tune to best meet our needs.

The documentation here is intended for:
- Current team members working on the car
- Future FSAE members inheriting this project
- Technical reference for control algorithms and software

---

## Roadmap
- **Phase 1 — Research & Rules**  
  Gather background on traction control, confirm legality in FSAE rules, and study ECU documentation.
- **Phase 2 — Arduino Setup, Determining Pi Feasability, Wheel Speed Sensing** 
  Determine if Pi is needed, write code for wheel speed sensing
---

## Repository Structure

fsae-tcs/
│── README.md # Project overview
│── docs/
│ ├── research.md # Notes from papers, videos, rulebook
│ ├── ecu.md # PE3 8400 details, configs, limitations
│── data/ # Log files, CSVs, test results, code