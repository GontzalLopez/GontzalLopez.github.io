---
layout: archive
title: ""
permalink: /tutorials/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Course on OpenFOAM. Numerical Wave Tanks - Day 1 Material (June 2024 Bilbao School of Engineering)
======

## Includes:

- Quick installation guide for OpenFOAM on Linux and Windows using WSL.
- Brief introduction to the OpenFOAM code and context, including the philosophy and general structure of the code.
- Tutorial on a floating object, creating the mesh with snappyHexMesh and introducing concepts of dynamic mesh with overset method.
[Download material folder](https://ehubox.ehu.eus/s/HM9jigPH9Yag38Z)

<p align="center">
  <img src='/images/animation_case.gif' alt="Alt Text" width="300"/>
</p>


Lid Driven Cavity - FVM Code in c++
======
- 2D LDC solver using FVM. Hybrid differencing scheme for convection-diffusion, SIMPLE algorithm for pressure velocity coupling. SOR (Successive Over Relaxation) was used to solve the pressure correction equation.
[Code](https://github.com/GontzalLopez/2D-Lid-driven-cavity)


2D Lattice-Boltzmann solver
======
- A Simple 2D Implementation of Lattice Boltzmann Method in c++. Allows the user to simulate the flow over a cylinder, array of squares or a rectangular obstacle. Top and bottom boundaries can be modelled as walls or periodic. The code was written for educational purposes as a basic introduction to the LBM models. The next step would be to write the code in order to parallelise the calculation and include turbulent LES models.
[Code](https://github.com/GontzalLopez/2D-Lattice-Boltzmann-solver)
