## Week 1: Projectile Motion without Air Drag

### Description

A simulation of classical projectile motion under constant gravity (ignoring air resistance). The simulation models the parabolic trajectory of an object launched at an angle with a given speed. This is part of a 4-week physics simulation mini-project series aimed at showcasing physics through interactive Python simulations.

### Features

- Compute and visualize projectile trajectory
- Interactivity using `ipywidgets` (sliders for launch speed and angle)
- Dynamic plot updates with real-time changes
- (Upcoming) Animation of projectile motion
- (Upcoming) Gravity comparison across planets

### Screenshots

```
[Coming Soon]
```

### Getting Started

#### Prerequisites

- Python 3.10+
- JupyterLab
- Install the required packages:

```bash
pip install matplotlib numpy ipywidgets
```

Make sure to enable `ipywidgets` in JupyterLab:

```bash
jupyter nbextension enable --py widgetsnbextension
```

> If you’re using JupyterLab 3+, this might not be needed.

### How to Run

Launch JupyterLab and open the `.ipynb` file.\
Adjust the sliders for **initial speed** and **angle** to explore different trajectories.

### Physics Background

The projectile motion is governed by the classical kinematic equations under constant acceleration due to gravity:

- Horizontal distance: `x(t) = v₀ cos(θ) * t`
- Vertical distance: `y(t) = v₀ sin(θ) * t - ½ g t²`

Where:

- `v₀` is the initial speed
- `θ` is the launch angle
- `g` is the gravitational acceleration (≈ 9.81 m/s² on Earth)

### Project Structure

```
Week1_ProjectileMotion_NoDrag/
├── Week1_ProjectileMotion_NoDrag.ipynb     # Main Jupyter notebook
├── simulation.py                           # Python script version (optional)
├── README.md                               # This file
└── media/                                  # Folder for images or GIFs (optional)
```

### Future Enhancements

- 🎞️ Animation with `FuncAnimation`
- 🌌 Compare motion under different planetary gravities
- 🎮 Add reset/start/pause buttons for animation
- 📄 Exportable reports from simulation results

### Author

**Dr. Parthasarathy R.**\
[GitHub Profile](https://github.com/dr-parthasarathy-r)

### License

This project is open source and available under the [MIT License](LICENSE)

