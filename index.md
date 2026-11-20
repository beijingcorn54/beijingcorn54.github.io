---
layout: single
author_profile: true
title: "Hi, I'm Katherine 👋"
---

I'm an Electrical Engineering student at the **University of Michigan** (B.S.E., expected December 2027, GPA 3.74). I focus on **embedded systems and sensor hardware**: designing PCBs, sensing circuits and the firmware that ties them together. I'm looking for **summer 2027 internships**.

[📄 Resume](/Fuller_Nov26.pdf){: .btn .btn--primary} [LinkedIn](https://linkedin.com/in/kefuller0){: .btn .btn--inverse} [Email](mailto:kefuller@umich.edu){: .btn .btn--inverse}

---

## Projects

### 🎈 Stratospheric Monitoring Device
*Electrical Lead, ENGR 100 design team · Jan – May 2025*

A sensing package that monitored local cloud formation aboard a high-altitude weather balloon, built with a 4-person team spanning electrical, mechanical and software.

- Designed **two custom PCBs** (power control + sensor interface) in Altium Designer and LTspice, and hand-soldered both boards, to measure stratospheric humidity, temperature and pressure
- System operated reliably at **–40 °F** through 2+ hours of flight turbulence and a hard landing

### ⚡ Electrical Measuring Device Replica (MRacing Formula SAE)
*Vehicle Software & Instrumentation team · Sept 2026 – present*

A replica of the FSAE competition energy meter that will let the team confirm the car's power-limit compliance (80 kW, 600 V DC) before competition.

- Authored and revised the requirements document, and diagrammed the vehicle's high-voltage path from accumulator through inverter to motor
- Specified a **500 kbaud CAN interface** (five messages) and a **120–150+ Hz** voltage/current sampling target, set with team mentors to catch violations defined over 100 ms windows
- Own the **MCU data and power inputs** subsystem. Redesigned it after an updated meter manual moved temperature data onto CAN, which passed design review and shrank the parts list
- Onboarding three new team members with a specs document and LTspice practice problems ahead of PCB layout in Altium

### 🦿 Torque Model for Lower-Limb Robotic Prostheses
*Student Researcher, Locomotor Control Systems Laboratory · Jan 2026 – present*

- Built a MATLAB pipeline to process motion-capture and force-plate data across **150 trials** (10 subjects × 3 walking speeds × 5 inclines), reconstructing lower-limb kinematics, ground reaction forces, cadence and stride length
- Found that cadence and normalized stride length separate stance-phase knee and ankle torque trajectories more cleanly than treadmill speed. Both can be computed onboard, but current controllers don't use them
- Designed an impedance-based torque scaling model that adds cadence and stride length as parameters, and validated it against the lab baseline using variance accounted for (VAF). Caught and fixed an analysis bug with unit tests and checks against published results
- Now integrating the model into the lab's prosthesis control code and testing it on a physical prosthetic leg

### 🧮 Verilog Four-Function Calculator
*Course project, Digital Logic Design (EECS 270) · Apr – May 2026*

- Designed a sequential calculator around finite-state-machine control logic
- Built arithmetic modules, including a full adder and an adder/subtractor, plus a binary-to-seven-segment display driver
- Verified correctness with ModelSim testbenches

### 🚌 Bus Tracking Device (MaizeBus)
*Nov 2026 – present*

Designing a new bus-tracking device for MaizeBus, a small bus-tracker startup. *Details coming soon.*

---

## Skills

- **Programming & HDL:** C/C++, Verilog, ARM (LEGv8) Assembly, Python, MATLAB
- **Engineering software:** Altium Designer, LTspice, ModelSim, Arduino
- **Hardware:** PCB design, hand soldering, CAN
- **Languages:** English, Mandarin Chinese

## Relevant Coursework

Electronic Circuits · Digital Logic Design · Computer Organization · Signals & Systems · Engineering Electromagnetism · Programming & Data Structures · Electronics for Atmospheric & Space Measurements

*Current (Fall 2026):* Digital Integrated Circuits · Digital Signal Processing · Electrical Biophysics

## Education & Activities

- **University of Michigan**, B.S.E. Electrical Engineering, expected Dec 2027. Dean's List and University Honors (multiple terms)
- **Shanghai Jiao Tong University**, study abroad, May – Aug 2025
- Grader, Engineering Electromagnetics, University of Michigan
- MRacing Formula SAE, Vehicle Software & Instrumentation team
