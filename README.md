# From Physics to Physiology

Course assignments for *From Physics to Physiology* at Vrije Universiteit Amsterdam (2025). The course covers computational modelling of vascular networks, bridging physical principles (fluid mechanics, electrical analogies, transport phenomena) with physiological applications in the cerebral vasculature.

## Contents

### Adaptation Project (`AdaptationProject-1/`)

MATLAB implementation of vascular network hemodynamics covering:

- **Network construction** -- honeycomb, Wheatstone bridge, and random graph geometries
- **Vessel adaptation** -- radius dynamics driven by wall shear stress
- **Thrombus formation and lysis** -- occlusion modelling with thrombolysis
- **Tracer transport** -- advective transport of a tracer through the network

Key entry points: `GoProject.m` (adaptation), `GoTroLyse.m` (thrombus/lysis), `Transport.m` (tracer transport).

### Exercises (`Exercises/`)

Weekly problem sets in MATLAB Live Scripts (`.mlx`) and Mathematica notebooks (`.nb`), including shear-stress demonstrations, a Windkessel model, and exam preparation.

### PyTorch Tutorial (`docs/`)

An introductory PyTorch notebook used alongside the course material.

## Requirements

- MATLAB (R2023a or later recommended)
- Wolfram Mathematica (for `.nb` notebooks)
- Python 3.10+ with PyTorch (for the tutorial notebook)

## How to Run

Open MATLAB, navigate to `AdaptationProject-1/`, and run any of the main scripts:

```matlab
cd AdaptationProject-1
GoProject        % vessel adaptation simulation
GoTroLyse        % thrombus formation and lysis
Transport        % tracer transport
```

For exercises, open the `.mlx` files in MATLAB or `.nb` files in Mathematica.

## Course

From Physics to Physiology -- Vrije Universiteit Amsterdam, 2025
