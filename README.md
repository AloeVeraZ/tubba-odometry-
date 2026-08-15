<div align="center">

# Tubba Odometry

### A compact spring-loaded dead-wheel odometry tracking pod for FTC robotics

[![FTC](https://img.shields.io/badge/Platform-FIRST_Tech_Challenge-00aeef?style=flat-square&logo=first&logoColor=white)](https://www.firstinspires.org/robotics/ftc)
[![Sensor](https://img.shields.io/badge/Encoder-REV_Through_Bore-6f42c1?style=flat-square)](https://www.revrobotics.com/rev-11-1271/)
[![CAD](https://img.shields.io/badge/CAD-STEP_%2F_ISO_10303-22c55e?style=flat-square)](cad/)
[![GrabCAD](https://img.shields.io/badge/GrabCAD-Public_Model-f57c00?style=flat-square)](https://grabcad.com/library/tubba-odometry-for-ftc-1)
[![License](https://img.shields.io/badge/License-CC_BY_4.0-f59e0b?style=flat-square)](LICENSE)

<picture>
  <img src="assets/images/assembly-render.png" alt="Tubba Odometry assembly render" width="820" draggable="false">
</picture>

A high-accuracy, passive dead-wheel odometry module engineered with AndyMark Dualie omni wheels and REV Through Bore Encoders for real-time planar localization.

<strong>Quick navigation:</strong><br>
[Module Overview](#what-is-tubba) | [Bill of Materials](#bill-of-materials) | [CAD Files](cad/) | [Gallery](#gallery) | [GrabCAD Model](https://grabcad.com/library/tubba-odometry-for-ftc-1)

</div>

---

## What is Tubba?

**Tubba** is a compact dead-wheel odometry pod engineered by FTC Team 9384 Hydraulic Hydras. It provides a passive, unpowered omni tracking wheel in continuous ground contact, measuring independent translational and rotational displacement for dead reckoning and localization libraries such as Road Runner.

The assembly is built around an AndyMark **2 in. Dualie Omni Wheel** (1/2" hex, 50A durometer) paired with a **REV Through Bore Optical Encoder**. It was designed to package compactly between the parallel structural plates of Team 9384's 2023–2024 robot, **EggWUUUHH**.

| Subsystem Specification | Technical Details |
| --- | --- |
| Tracking wheel | AndyMark 2 in. Dualie Omni Wheel (50A durometer for low lateral scrub) |
| Encoder type | REV Through Bore Optical Shaft Encoder (8192 counts/rev in quadrature) |
| Suspension & preload | Surgical tubing / spring tensioned pivot for continuous floor compliance |
| Mounting architecture | Direct plate mounting with integrated flanged hex bearings |
| Hardware standard | M3 socket head cap screws + hex nuts |

> [!NOTE]
> The STEP solid model serves as the dimensional source of truth. Validate your 3D printer slicing tolerances, bearing press-fits, and robot frame clearances before volume manufacturing.

## Gallery

<div align="center">

| Physical Assembled Prototype | Master CAD Solid Assembly |
| :---: | :---: |
| <img src="assets/images/prototype-photo.jpg" alt="Tubba Odometry prototype" width="100%"> | <img src="assets/images/assembly-render.png" alt="Complete Tubba Odometry CAD assembly" width="100%"> |

</div>

<div align="center">

| Sensor Side Plate CAD | Outer Retaining Plate CAD |
| :---: | :---: |
| <img src="assets/images/sensor-plate-render.png" alt="Sensor plate CAD render" width="100%"> | <img src="assets/images/outer-plate-render.png" alt="Outer plate CAD render" width="100%"> |

</div>

## Bill of Materials

Sourcing list for **one odometry module** (mirrors the original Team 9384 BOM):

| Item | Component Description | Supplier / Source | Part Number | Qty. | Direct Link |
| :---: | --- | --- | --- | :---: | :---: |
| 1 | 3D-Printed Structural Plates | 3D Printed (PETG/PLA) | `cad/` | 1 set | [View Models](cad/) |
| 2 | Optical Through Bore Encoder | REV Robotics | REV-11-1271 | 1 | [REV Store](https://www.revrobotics.com/rev-11-1271/) |
| 3 | 2" Dualie Omni Wheel (1/2" Hex, 50A) | AndyMark | am-4684_50A | 1 | [AndyMark Store](https://www.andymark.com/products/2-in-dualie-omni-wheel) |
| 4 | 1/2" Hex Flanged Bearing (FR8ZZ-HexHD) | AndyMark | FR8ZZ-HexHD | 1 | [AndyMark Store](https://www.andymark.com/products/0-5-in-hex-id-1-125-in-od-shielded-flanged-bearing-fr8zz-hexhd) |
| 5 | 5 mm Hex Shaft Stock | REV Robotics | REV-41-1362-PK4 | 1 | [REV Store](https://www.revrobotics.com/5mm-Hex-Shafts/) |
| 6 | 3 mm ID Preload Surgical Tubing | REV Robotics | REV-41-1163 | 1 | [REV Store](https://www.revrobotics.com/rev-41-1163/) |
| 7 | M3 × 45 mm Socket Head Screws | Fastener Supply | — | 1 pack | [Amazon](https://www.amazon.com/dp/B0967ZTRXB) |
| 8 | M3 Nylon-Insert Lock Nuts | Fastener Supply | — | 1 pack | [Amazon](https://www.amazon.com/dp/B0CR3S4MZT) |

Portable tabular BOM data is preserved in [`docs/BOM.csv`](docs/BOM.csv) and [Google Sheets](https://docs.google.com/spreadsheets/d/17jjdt58DgWxnq1DswMJ4VjZQLS4xurBlHhdxET_VKbg/edit?usp=sharing).

## CAD Collection

Neutral ISO 10303 STEP exports in [`cad/`](cad/):
- [`cad/9384 odom final v1.step`](cad/9384%20odom%20final%20v1.step): Master assembled module
- [`cad/sensor plate.step`](cad/sensor%20plate.step): Inner encoder mounting plate
- [`cad/outter plate.step`](cad/outter%20plate.step): Outer bearing retaining plate
- [`cad/hex shaft mod.step`](cad/hex%20shaft%20mod.step): Machined hex shaft profile

## License & Attribution

Original design, models, and documentation © 2024–2026 **Angelo Demetroulakos**. Licensed under the **[Creative Commons Attribution 4.0 International License](LICENSE)**.

```text
Based on Tubba Odometry for FTC by Angelo Demetroulakos and FTC Team 9384 Hydraulic Hydras,
licensed under CC BY 4.0. Source: https://grabcad.com/library/tubba-odometry-for-ftc-1
```
