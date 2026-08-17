# 🤖 Industrial Robotics Lab Projects

This repository contains lab work from the **Industrial Robotics Laboratory** (Group 2A) at Hochschule Ravensburg-Weingarten, covering hands-on **KUKA industrial robot** programming — from tool/base calibration and KUKA.Sim simulation through to deploying and validating programs on a real robot.

Full write-up: [Robotics_report.pdf](./Robotics_report.pdf)

## Team

- Arjun Rameshbhai Beladiya
- Dhaval Jagdish Mistry
- Tarang Chimanbhai Italiya

**Supervisor:** Prof. Dr.-Ing. Konrad Wöllhaf

## Key Outcomes

- Successfully taught tool center points (4-point method) and workpiece base coordinates, and validated that a box-following program adapted correctly after the base was re-taught to a new box position — with no program changes required.
- Programmed and simulated shape-drawing routines (rectangle, "house of Santa Claus") in KUKA.Sim using `WAIT`, `WHILE`, and `IF` control structures driven by digital inputs.
- Designed, simulated, and extended a color-based ball-sorting program: the extended version keeps sorting other colors once one pallet is full, instead of halting the whole process.
- Deployed the sorting program to a physical KUKA robot, configured digital I/O for color/ball-presence sensors, and validated performance through incremental speed testing (low → full operating speed), with final sign-off from the lab supervisor.

---

## 1️⃣ Teaching Tool and Base, Simple Program

Taught the tool center point using the KUKA 4-point method, calibrated the base coordinate system of a workpiece box using three non-collinear reference points, and wrote a PTP/LIN program to trace the box's edges. Re-taught the base after the box was moved and confirmed the program adapted correctly to the new position.

## 2️⃣ KUKA.Sim Programming

Programmed the robot in KUKA.Sim to draw a rectangle and the "house of Santa Claus" figure using a tool exchanged from the tool magazine. Used `WAIT`, `WHILE`, and `IF` logic with digital inputs (`IN[12]`, `IN[13]`, `IN[14]`) mapped to red/green/blue buttons to control which shape the robot draws.

## 3️⃣ Ball Sorting Simulation

Designed a flowchart and KRL program to pick balls from a feeder, detect their color via sensor signals, and place them onto color-matched pallets, tracking counts per color. Extended the base version so that when one pallet becomes full, the robot no longer halts — it keeps sorting balls destined for non-full pallets and only discards balls matching the full pallet, continuing until all three pallets reach capacity.

## 4️⃣ Real-Robot Implementation

Transferred the simulated program to a physical KUKA robot, configured digital inputs for ball-color and ball-presence sensors, and validated all taught points. Tested incrementally from low to normal operating speed, confirming reliable gripper, sensor, and sorting behavior before final supervisor approval.

## Tech / Tools

- KUKA.Sim (simulation)
- KRL (KUKA Robot Language)
- KUKA industrial robot (KRC controller, KCP2 teach pendant)
- PTP / LIN / CIRC motion programming, digital I/O signal handling

## Repo Structure

```
├── README.md
└── Robotics_report.pdf   # Full lab report (4 labs, methodology, code, results)
```
