# Collisions

A modern C++ project exploring collision detection, collision response and real-time physical simulation through interacting spheres within a constrained environment.

Collisions investigates the mathematical and software engineering principles behind collision processing by simulating multiple spheres falling under gravity into an inverted pyramid. Rather than focusing on gameplay or engine architecture, the project explores how geometric representation, collision detection and response calculations combine to produce stable and believable physical interactions.

The project focuses on algorithm implementation, computational geometry and modular software design, demonstrating how collision systems can be organised into clear, maintainable components while applying concepts commonly found in physics engines and real-time simulations.

---

## The Engineering Problem

Collision processing is a fundamental requirement for many real-time applications, yet implementing reliable collision systems involves significantly more than detecting overlapping objects. Dynamic bodies must interact consistently with one another and their environment while maintaining stable behaviour across repeated collisions.

Collisions explores this challenge by implementing the algorithms required to detect and resolve interactions between multiple moving spheres and the static faces of an inverted pyramid. The project investigates how collision detection, response calculations and supporting mathematics can be organised into a maintainable C++ application while demonstrating the core concepts underpinning real-time physics simulation.

---

## Simulation Architecture

<p align="center">
  <img width="700" alt="RealTimeCollisionHandling" src="https://github.com/user-attachments/assets/7cd6d959-020f-4f6b-a9f6-d48b896cf515" />
</p>

The simulation is organised into modular systems responsible for object representation, collision detection, collision response and supporting mathematical operations. Each subsystem performs a focused responsibility while contributing to the overall simulation, allowing collision processing to remain clearly separated from simulation management and rendering.

---

## Engineering Goals

The project was designed to explore:

- Collision detection algorithms
- Collision response techniques
- Sphere-to-sphere interactions
- Sphere-to-environment collisions
- Computational geometry
- Vector mathematics
- Real-time simulation
- Modular software organisation

Although demonstrated through spheres interacting within an inverted pyramid, the engineering concepts explored are applicable to graphics engines, simulation software and interactive real-time applications.

---

## Key Features

- Multi-body sphere simulation under gravity
- Sphere-to-sphere collision detection and response
- Sphere-to-environment collision handling
- Inverted pyramid collision boundaries
- Collision normal and response calculations
- DirectXMath vector mathematics
- Modular collision processing systems
- Stable real-time simulation behaviour

---

## Technologies & Engineering Practices

### Development

- C++20
- DirectXMath
- Visual Studio 2022
- Git
- Git Submodules

### Engineering Practices

- Collision Detection
- Collision Response
- Computational Geometry
- Real-Time Simulation
- Object-Oriented Design
- Separation of Concerns
- Modular Software Design
- Vector Mathematics
- Mathematical Optimisation
- Performance-Oriented Programming

---

## Architecture Highlights

- Collision detection separated from collision response
- Modular simulation components with focused responsibilities
- Sphere-to-sphere and sphere-to-environment interactions
- Geometric primitives driving collision calculations
- DirectXMath SIMD vector mathematics
- Stable multi-object collision processing

---

## Engineering Outcome

Collisions demonstrates how the mathematical principles behind real-time collision processing can be translated into a structured C++ application. By simulating multiple spheres interacting within an inverted pyramid, the project explores collision detection, collision response and computational geometry while maintaining a modular software architecture.

Rather than functioning as a complete physics engine, the project serves as a practical investigation into collision processing, demonstrating experience with vector mathematics, geometric algorithms and the engineering considerations involved in building stable real-time simulations.

---
