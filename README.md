# Sigma–Delta Modulator – Cadence Virtuoso

This repository contains the complete design and simulation of a
**first-order Sigma–Delta Modulator** implemented using
**Cadence Virtuoso**.

The modulator integrates the following verified blocks:
- Integrator
- Quantiser (Comparator-based)
- 1-bit feedback DAC

## Tool Used
- Cadence Virtuoso (Analog Design Environment)
- Spectre Simulator

## Library Name
- sigma_delta_modulator

## Cells Included
- **slope_1** : Top-level Sigma–Delta modulator schematic

## Architecture
The Sigma–Delta modulator consists of:
- A summing node (error computation)
- Integrator (sigma operation)
- Quantiser (1-bit output)
- Feedback DAC loop (delta operation)

## Simulations
- Transient analysis
- Input: Analog signal
- Output: 1-bit high-frequency digital stream
- Output bit density represents input amplitude

## Screenshots
The `screenshots/` folder contains:
- Sigma–Delta modulator schematic
- Transient simulation showing 1-bit output and integrator response

## Project Team
This project was carried out as a **group mini-project**.

### Team Members
- Likhith Gowda H R
- Dhruthi Sridhar
- Adith Soragu
