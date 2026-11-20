---
layout: single
author_profile: true
title: "Hi, I'm Katherine 👋"
excerpt: "Electrical Engineering @ University of Michigan · Embedded systems, PCBs & sensor hardware"
---

I'm an Electrical Engineering student at the **University of Michigan** (B.S.E., expected December 2027, GPA 3.74). I like hardware I can hold: I've designed and hand-soldered PCBs that flew to the stratosphere, I'm building a high-voltage energy meter for a Formula SAE car, and I test control models on real robotic prostheses.

I'm looking for **summer 2027 internships** in embedded systems, hardware or electronics manufacturing.

[📄 Resume](/Fuller_Nov26.pdf){: .btn .btn--primary} [LinkedIn](https://linkedin.com/in/kefuller0){: .btn .btn--inverse} [Email me](mailto:kefuller@umich.edu){: .btn .btn--inverse}

**At a glance:** 2 custom PCBs designed, hand-soldered and flown at –40 °F · 600 V / 80 kW FSAE energy meter in design · 150-trial gait dataset analyzed · TA for 200+ students
{: .notice--info}

---

## Projects

### 🎈 Stratospheric Monitoring Device
*Electrical Lead · ENGR 100 design team · Jan – May 2025*

A sensing payload that monitored local cloud formation from a high-altitude weather balloon, built with a 4-person team spanning electrical, mechanical and software.

- **Designed two custom PCBs** in Altium Designer and LTspice: a power-control board (SOT-223 LDO regulators for the 3.3 V and 5 V rails, TVS transient protection) and a sensor-interface board linking an Arduino Nano, an OpenLog data logger, a level shifter and the humidity, temperature and pressure sensors
- **Hand-soldered both boards myself**, a mix of 1206 SMD passives and through-hole headers. I tack-soldered passives to prevent tombstoning, managed heat on the regulators' copper-pour tabs to avoid cold joints, inspected every fillet, and continuity-checked each rail before powering the MCU
- **Result:** both boards powered up on the first integrated test and logged data for the full 2+ hour flight at about **–40 °F**, through turbulence and a hard landing, with no failed joints

### ⚡ Electrical Measuring Device Replica · MRacing Formula SAE
*Vehicle Software & Instrumentation team · Sept 2026 – present*

At competition, a car is disqualified if it draws more than **80 kW for over 100 ms**. The official energy meter can't be bought, so our team is building a replica that lets the powertrain team check new designs against the limit before competition.

- **Wrote the requirements document from scratch** using the EMeter user manual, the 2027 FSAE rules and input from team mentors. It's now the baseline the whole team designs against
- **Diagrammed the 600 V DC high-voltage path** from accumulator through inverter to motor, locating the meter's series current measurement and HV sense connections
- **Specified a 500 kbaud CAN interface** (five messages) and a **120–150+ Hz** voltage/current sampling target, faster than the official meter, so the powertrain team gets better data
- **Own the MCU data and power inputs subsystem** (GLV power input, signal conditioning, CAN transceiver). When an updated meter manual moved temperature data onto CAN mid-design, I led the team's review of the changes and redesigned my subsystem. It passed design review with a shorter parts list
- **Onboarding three new members** who joined from a dissolved project: I wrote an LTspice practice circuit with an answer key and give each person feedback, so they're ready for PCB layout in Altium

### 🦿 Torque Model for Lower-Limb Robotic Prostheses
*Student Researcher · Locomotor Control Systems Laboratory (LocoLab) · Jan 2026 – present*

- **Built a MATLAB pipeline** to process motion-capture and force-plate data across **150 trials** (10 subjects × 3 walking speeds × 5 inclines), reconstructing lower-limb kinematics, ground reaction forces, cadence and stride length
- **Found that cadence and normalized stride length** separate stance-phase knee and ankle torque trajectories more cleanly than treadmill speed. Both can be computed onboard, but current controllers don't use them
- **Designed a new impedance-based torque model** that adds cadence and stride length as parameters, and benchmarked it against the lab's baseline using VAF and RMSE for every subject, speed and incline
- **Caught my own analysis bug:** early results looked too good, so I wrote unit tests for each pipeline step, traced the error to un-updated optimization functions, and validated the corrected pipeline by reproducing a published result
- **Now testing on a physical prosthesis**, using code generated from the lab's control codebase, and analyzing the joint stiffness results across the gait cycle

### 🧮 Verilog Four-Function Calculator
*Course project · Digital Logic Design (EECS 270) · Apr – May 2026*

- Designed a sequential calculator around finite-state-machine control logic
- Built arithmetic modules (full adder, adder/subtractor) and a binary-to-seven-segment display driver
- Verified correctness with ModelSim testbenches

### 🌪️ Wind-Induced Structural Response Modeling
*Student Researcher · ResLab · Jan – May 2025*

- Contributed to a computational model predicting how large structures respond to extreme wind events like hurricanes and tornadoes
- Trained a feedforward neural network in PyTorch that reached **98%+ accuracy** predicting continuous functions from synthetic datasets

### 🚌 Bus Tracking Device · MaizeBus
*Hardware design · Nov 2026 – present*

Designing a new bus-tracking device for MaizeBus, a small bus-tracker startup. *Details coming soon.*

---

## Teaching

- **Grader, Engineering Electromagnetics**, University of Michigan · Fall 2026
- **Teaching Assistant, General Physics II** (calculus-based E&M), Physics Student Services · Sept 2025 – Jan 2026: co-led discussion and practice sessions for **200+ students**, led exam reviews for 80+ students, and held weekly office hours

## Skills

| | |
|---|---|
| **Hardware** | PCB design, hand soldering (SMD & through-hole), CAN, circuit simulation, lathe & mill |
| **Programming & HDL** | C/C++, Verilog, ARM (LEGv8) Assembly, Python, PyTorch, MATLAB |
| **Tools** | Altium Designer, LTspice, ModelSim, Arduino, Git |
| **Languages** | English, Mandarin Chinese |

## Relevant Coursework

Electronic Circuits · Digital Logic Design · Computer Organization · Signals & Systems · Engineering Electromagnetism · Programming & Data Structures · Electronics for Atmospheric & Space Measurements

*Current (Fall 2026):* Digital Integrated Circuits · Digital Signal Processing · Electrical Biophysics

## Education

- **University of Michigan**, B.S.E. Electrical Engineering, expected Dec 2027 · GPA 3.74 · Dean's List & University Honors (multiple terms)
- **Shanghai Jiao Tong University**, study abroad · May – Aug 2025

## Outside the Lab

Rock climbing, Gymnastics, and Powerlifting with University of Michigan clubs.
