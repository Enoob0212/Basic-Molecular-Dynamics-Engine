# Basic-Molecular-Dynamics-Engine
MDEngine is a compact, extensible molecular dynamics (MD) engine designed for rapid experimentation, educational use, and scientific prototyping. It implements a 3D particle simulation with Langevin dynamics, customizable physical parameters, optional real‑time visualization, and automated post‑simulation analysis. This engine is ideal for users who want a transparent, easy‑to‑modify MD codebase without the overhead of large simulation frameworks.

Key Features
- Langevin Dynamics Integrator
Simulates particle motion under friction and stochastic thermal noise, enabling canonical ensemble sampling.
- Configurable Physical Parameters
Control particle count, box size, timestep, friction coefficient, thermal energy k_{\mathrm{B}}T, and particle size.
- 3D Simulation Box
Particles evolve inside a cubic domain with periodic or reflective boundary handling (depending on your implementation).
- Optional VPython Visualization
Real‑time 3D rendering of particle trajectories for intuitive understanding of system behavior.
- Built‑in Data Logging
Tracks velocities, kinetic energy, potential energy, total energy, and time history throughout the simulation.
- Automated Analysis Tools
Includes velocity distribution histograms, Maxwell–Boltzmann fitting, radial distribution calculations, running coordinate numbers, and energy‑vs‑time diagnostics.

