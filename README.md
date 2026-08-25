# Autonomous Green Hydrogen Power Plant Controller — Milestone 1

Milestone 1 establishes the source and input–output specifications for an educational autonomous green-hydrogen plant controller based on Mamdani fuzzy logic.

## Scope

The controller specification defines four inputs and one output:

| Signal | Role | Range | Linguistic terms |
|---|---|---:|---|
| Renewable power | Input | 0–100 kW | Low, Medium, High |
| Water flow rate | Input | 0–20 L/min | Low, Medium, High |
| Stack temperature | Input | 20–80 °C | Low, Normal, High |
| Hydrogen-tank pressure | Input | 0–100 bar | Low, Medium, High |
| Hydrogen production rate | Output | 0–10 kg/h | Off, Low, Medium, High |

The supplied source specification defines the triangular membership points and 11 expert rules used by later implementation, testing, analysis, and UI milestones. The hydrogen-tank pressure input is safety-critical: production should be reduced as tank pressure approaches the high-pressure region.

## Contents

- `docs/Milestone_1_Source_Specification.pdf` — source specification presentation.
- `docs/Milestone_1_IO_Specification.md` — concise machine-readable summary of the controller signals and requirements.

## Project Context

This milestone is the specification foundation for subsequent phases that implement the fuzzy controller, exercise input combinations, analyze controller behavior, and expose live controls.

## Safety Disclaimer

This repository contains an educational simulation specification. It is **not** a certified process-safety system and must not be used to control real hydrogen-production equipment without appropriate engineering validation, hardware safeguards, regulatory review, and qualified professional oversight.

## Authors

Krupa Ashishkumar Rajput; Jaimin Sanghani; Harsh Shingala; Makwana Shlock.

## License

No license has been specified for this milestone.
