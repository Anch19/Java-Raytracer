````md
# Java-Raytracer

A lightweight **Java-based ray tracing engine** developed as a computer graphics and software engineering project.  
The project focuses on implementing core rendering concepts from scratch, including ray-object intersections, shading models, 3D object loading, and acceleration structures for efficient rendering.

The renderer supports spheres, planes, triangle meshes, OBJ file loading, and realistic lighting using the **Phong illumination model**.

---

# Features

- Ray tracing engine implemented in Java
- Sphere and plane rendering
- Triangle mesh support
- OBJ model loading
- Phong shading implementation
- Reflection and lighting calculations
- BVH (Bounding Volume Hierarchy) acceleration structure
- Modular object-oriented architecture
- Scene rendering and image generation
- Test package for validation and debugging

---

# Project Structure

```bash
Java-Raytracer/
├── src/
│   └── raytracer/
│       ├── core/        # Rendering pipeline and ray tracing logic
│       ├── geom/        # Geometric primitives and intersections
│       ├── math/        # Vector and mathematical utilities
│       ├── shade/       # Lighting and shading models
│       ├── tests/       # Testing utilities
│       └── Main.java
│
├── obj/                 # 3D object models (.obj files)
├── README.md
└── ...
````

---

# Rendering Concepts Implemented

## Ray Tracing

The engine simulates the behavior of light rays to determine visible surfaces and lighting interactions within a 3D scene.

## Phong Shading

Implements ambient, diffuse, and specular lighting components for realistic illumination.

## OBJ Model Loading

Supports importing external `.obj` mesh files for rendering custom 3D geometry.

## BVH Acceleration

Uses Bounding Volume Hierarchies to reduce intersection tests and improve rendering performance.

---

# Technologies Used

* Java
* Object-Oriented Programming (OOP)
* Computer Graphics Algorithms
* BVH Spatial Acceleration
* OBJ File Parsing

---

# How to Run

## Clone the Repository

```bash
git clone https://github.com/Anch19/Java-Raytracer.git
cd Java-Raytracer
```

## Compile

```bash
javac src/raytracer/Main.java
```

## Run

```bash
java raytracer.Main
```

> The exact entry point may vary depending on your IDE or project setup.

---

# Example Features Demonstrated

* Rendering spheres and planes
* Mesh rendering using OBJ models
* Shadow computation
* Surface reflections
* Lighting calculations
* Scene intersection optimization

---

# Learning Outcomes

This project was developed to strengthen understanding of:

* Computer graphics fundamentals
* Ray tracing algorithms
* 3D mathematics and vector operations
* Spatial acceleration structures
* Object-oriented software design
* Performance optimization techniques
* Rendering pipelines

---

# Future Improvements

Potential future enhancements include:

* Texture mapping
* Refraction and transparency
* Anti-aliasing
* Soft shadows
* Multithreaded rendering
* Global illumination
* Real-time scene controls
* GUI-based renderer preview

---

# Repository

[https://github.com/Anch19/Java-Raytracer](https://github.com/Anch19/Java-Raytracer)

---

# Author

Antriksh Chaudhary

Computer Graphics & Rendering Project





