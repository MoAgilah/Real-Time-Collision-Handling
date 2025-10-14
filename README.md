# Real-Time Collision Handling

A real-time collision detection and response system written in **C++**, featuring narrow-phase intersection tests, a simple broad-phase, and impulse-based resolution within an interactive DirectX sandbox.  

The project was originally developed using **DirectX 11**, with ongoing exploration toward **DirectX 12** and modern rendering techniques.

---

## 🎥 Preview

![Preview](Assets/preview.gif)

*(Demo visualising real-time sphere, ray, and polygon collisions in motion)*

---

## 📁 Project Structure

```
Collision/    → Collision detection and response logic (your implementation)
Shared/       → Provided runtime framework for rendering, input, and camera
*.sln         → Visual Studio solution file
```

> The **`Shared/`** folder was **provided by the course lecturer** and distributed to all students.  
> It serves as scaffolding for visualising and testing your collision system — no internal modifications are required.

---

## ⚙️ Features

- **Sphere–Sphere Collision Detection**  
- **Ray–Sphere Intersection**  
- **Ray–Cylinder Intersection**  
- **Ray–Triangle Intersection**  
- **Sphere–Polygon Tests**  
- **1D Sweep and Prune (Broad-Phase)**  
- **Impulse-Based Collision Resolution**  
- **Come-to-Rest and Bounce Handling**

---

## 🎮 Controls

| Key | Action |
|-----|--------|
| Space | Toggle 1 FPS slow motion |
| W | Toggle wireframe mode |
| C | Switch camera view (Side / Top) |
| R | Drop a ball on a random triangle |
| T | Drop a ball on the flat top triangle |
| U / I | Move marked triangle (Left / Right) |
| D | Drop a debug ball at predefined points |
| N | Move debug-ball target |
| E | Deactivate all active balls |
| F | Drop a ball on a marked triangle & its inverse |
| G / H | Disable / re-enable bottom triangles |
| ↑ / ↓ | Increase / decrease number of balls |
| B | Drop configured number of balls |
| M | Cycle through heightmaps |

**Camera Controls (Side View):**

| Key | Action |
|-----|--------|
| Q | Zoom in |
| A | Zoom out |
| O | Rotate left |
| P | Rotate right |

---

## 🧱 Building the Project

**Requirements**
- Visual Studio 2019 or 2022  
- Windows 10/11 SDK  
- DirectX 11 (legacy) or compatible DX12 setup  

**Steps**
1. Open `Real Time Collision Handling.sln`.  
2. Set the build configuration to **x64 → Debug** or **Release**.  
3. Press **F5** to build and run the demo.

---

## 🚀 Integration

The `Collision/` module can be reused independently of the provided demo viewer.  

To integrate it into another project:
- Include the headers from `Collision/`.
- Replace `Shared/` types with your own math and engine types as needed.
- Hook the update and resolution functions into your own game loop or physics system.

---

## 🔭 Future Improvements

- Enhanced resting state and friction simulation  
- Bounding Volume Hierarchy (BVH) integration  
- Optimised real-time checks for large object counts  

---

## 🙏 Acknowledgements

- **`Shared/`** scaffolding and runtime viewer were **provided by the course lecturer** and distributed to all students for demonstration purposes.  
- The **collision-handling logic** within `Collision/` was independently implemented by the author.  
- DirectX documentation and course materials were referenced for rendering and runtime setup.
