# V2X-mimo-microstrip-antenna
# Design and Optimization of a Two-Element 5.9 GHz MIMO Microstrip Patch Antenna for V2X Applications

## Overview

This project presents the design and optimization of a two-element MIMO microstrip patch antenna operating at 5.9 GHz for Vehicle-to-Everything (V2X) communication applications.

The antenna was designed and simulated using CST Studio Suite. Various optimization studies were performed, including patch length tuning, element spacing analysis, MIMO performance evaluation, and a Defected Ground Structure (DGS) investigation.

---

## Objectives

- Design a compact 5.9 GHz MIMO antenna
- Achieve low return loss and VSWR
- Minimize mutual coupling between antenna elements
- Evaluate MIMO diversity performance
- Optimize antenna dimensions using parameter sweeps

---

## Software Used

- CST Studio Suite
- Frequency Domain Solver

---

## Antenna Specifications

| Parameter | Value |
|------------|---------|
| Operating Frequency | 5.9 GHz |
| Substrate Material | FR4 |
| Substrate Height | 1.6 mm |
| Patch Length | 20 mm |
| Patch Width | 11.6 mm |
| Feed Length | 7.25 mm |
| Feed Width | 2.5 mm |
| Element Spacing | 20 mm |

---

## Performance Results

| Metric | Value |
|----------|----------|
| S11 | ~ -44 dB |
| S22 | ~ -42 dB |
| Isolation (S21) | ~ -48 dB |
| VSWR | ~ 1.01 |
| ECC | ~ 1×10⁻⁵ |
| Diversity Gain | ~ 10 dB |
| Directivity | ~ 4.85 dBi |

---

## Optimization Studies

### Inter-Element Spacing Sweep

Spacing values investigated:

- 20 mm
- 22 mm
- 24 mm
- 26 mm

### Patch Length Sweep

Patch lengths investigated:

- 19 mm
- 19.5 mm
- 20 mm

### DGS Investigation

A rectangular Defected Ground Structure (DGS) was introduced and analyzed. The results indicated negligible improvement because the baseline antenna already exhibited excellent isolation and ECC performance.

---

## Repository Contents

- CST simulation model
- Antenna geometry
- S-parameter results
- VSWR plots
- ECC analysis
- Diversity Gain analysis
- Radiation patterns
- Project documentation

---

## Author

Suyash Shah
