# Real-Time Collision Handling

A modular **C++ collision detection and response system** for real-time game simulation. The project implements narrow-phase intersection tests, a simple broad-phase, and impulse-based collision response within an interactive DirectX sandbox.

Originally developed with **DirectX 11**, with future exploration toward DirectX 12 and modern rendering workflows.

---

## 🎥 Preview

![Preview](https://raw.githubusercontent.com/MoAgilah/Real-Time-Collision-Handling/master/Previews/Gifs/Demo.gif)

---

## ⚙️ Key Features

- Sphere–Sphere collision detection
- Ray–Sphere, Ray–Cylinder, and Ray–Triangle intersection tests
- Sphere–Polygon collision tests
- 1D Sweep and Prune broad-phase
- Impulse-based collision response
- Bounce and come-to-rest handling
- Modular collision logic separated from rendering and input systems

---

## 🧱 Architecture

The project separates collision detection and response logic from the provided rendering framework. The core `Collision/` module is designed to be reusable and adaptable for future engine integration.

```text
Collision/    → Collision detection and response logic
Shared/       → Provided DirectX runtime framework
*.sln         → Visual Studio solution file
```

The `Shared/` folder was provided as course scaffolding for rendering, input, and camera control. The collision-handling logic in `Collision/` was independently implemented.

---

## 🛠 Technologies

- C++
- Visual Studio
- DirectX 11
- Real-time simulation
- Collision detection and physics response

---

## 🚀 Build & Run

### Requirements

- Visual Studio 2019 or 2022
- Windows 10/11 SDK
- DirectX 11-compatible setup

### Steps

1. Clone the repository.
2. Open `Real Time Collision Handling.sln`.
3. Set the configuration to **x64 → Debug** or **Release**.
4. Build and run the project.

A standalone executable is also available in the repository release/download section.

---

## 🔭 Future Work

- Bounding Volume Hierarchy integration
- Spatial partitioning structures
- Improved friction and resting-state handling
- Debug visualisation tools
- ECS or engine-level integration
- Multi-threaded collision processing

---

## 🙏 Acknowledgements

- The `Shared/` runtime framework was provided as university course scaffolding.
- Collision detection and response systems within `Collision/` were independently implemented by the author.
- DirectX documentation and course materials were referenced for rendering and runtime setup.

---

## 👤 Author

**Mohamed Agilah**  
🎓 Games Programmer & AI Developer  
🌐 https://moagilah.com/  
📧 agilahmohamed@gmail.com
