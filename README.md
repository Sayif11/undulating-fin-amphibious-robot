# undulating-fin-amphibious-robot#
# Adaptive Undulating-Fin Amphibious Robot

This repository contains MATLAB simulation models developed for the study of terrestrial
locomotion of a Velox-inspired amphibious robot using bio-inspired undulating fins.

The work focuses on understanding fin–ground interaction, postural stability, and actuator
loading when aquatic undulatory propulsion strategies are adapted for solid substrates.

---

## Project Overview

Amphibious robots operating in littoral zones require propulsion mechanisms that function
across water, soft terrain, and rigid ground without explicit mode switching. Inspired by the
Velox robot, this project investigates undulating-fin locomotion on land and addresses the
pitch and roll instability that arise due to synchronous fin actuation under gravitational
loading.

Two computational models were developed:
- A simplified **rigid ray-based dynamic model** for stability and gait analysis
- A **high-fidelity mass–spring soft-body model** for compliant fin–ground interaction

---

## Models Included

### 1. Ray-Based Rigid Fin Model
- Discrete actuator-driven fin rays
- Traveling-wave kinematics
- Penalty-based ground contact formulation
- Anisotropic friction model
- Used for pitch and roll stability analysis and gait phase studies

### 2. Mass–Spring Compliant Fin Model
- Kelvin–Voigt viscoelastic mesh representation of fins
- Distributed ground contact and deformation
- Virtual actuation through column-wise bending
- Actuator torque estimation and feasibility verification

---

## Simulation Environment

- MATLAB (R2021a or later recommended)
- Semi-implicit Euler integration
- Penalty-based normal contact and friction modeling

---

## How to Run

1. Open MATLAB
2. Navigate to the desired model directory
3. Run the main simulation script:

```matlab
main_ray_simulation
