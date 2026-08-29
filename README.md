## Project Website

[Autonomous Green Hydrogen Power Plant Controller](https://jaimins2002-netizen.github.io/Autonomous_Green_Hydrogen_Controller_Web.ghithub.io/milestone1/)



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

## 📖 Overview
Milestone 1 defines the controller specification for an educational Autonomous Green Hydrogen Power Plant Controller. It establishes the input-output contract, operating ranges, membership functions, and fuzzy rule base that serve as the foundation for all later milestones.

## 🎯 Objective
- Define the controller architecture.
- Specify controller inputs and outputs.
- Document operating ranges and linguistic variables.
- Establish the fuzzy logic rule base.
- Provide a common reference for implementation and testing.

## ⚙️ Controller Inputs
- Renewable Power (kW)
- Water Flow Rate (L/min)
- Stack Temperature (°C)
- Hydrogen Tank Pressure (bar)

## 📤 Controller Output
- Hydrogen Production Rate (kg/h)

## 🧠 Fuzzy Logic Features
- Mamdani Fuzzy Inference System
- Triangular Membership Functions
- Expert Rule Base
- Defuzzification for crisp output generation

## 📁 Repository Structure
```
docs/
├── Milestone_1_Source_Specification.pdf
└── Milestone_1_IO_Specification.md
```

## 🔒 Safety Note
This project is intended for educational and research purposes only. It is not designed or certified for controlling real hydrogen production systems.

## 🚀 Next Milestone
Milestone 2 implements the fuzzy controller defined in this specification using Python and scikit-fuzzy.

## 👥 Authors
- Krupa Ashishkumar Rajput
- Jaimin Sanghani
- Harsh Shingala
- Makwana Shlock
