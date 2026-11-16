# Raytracer — 3D rendering engine in C++

[![Epitech: Tek2](https://img.shields.io/badge/Epitech-Tek2-005696.svg)](https://www.epitech.eu/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)


A rendering engine that generates images by **simulating the inverse path of light**,
ray by ray. It reads a scene description (camera, primitives, lights…) and computes the
final color of every pixel — shadows, materials and reflections included.

Built as a team project at Epitech.

## ✨ Features

- 🔺 Primitives: spheres, planes (+ cylinders, cones…)
- 💡 Lighting: directional & ambient lights, drop shadows
- 🎨 Materials, reflections and per-pixel color computation
- 🔌 **Plugin system** (`.so`) to add primitives and effects without touching the core
- 📄 External scene description files (camera, objects, lights)
- 🖼️ Output to a PPM image file

## 🛠️ Tech stack

- **Language**: C++
- **Architecture**: object-oriented, interfaces, dynamic-library plugins
- **Maths**: ray/object intersections, dot products, illumination model
- **Build**: Makefile

## 🚀 Build & run

```bash
make
./raytracer scenes/example.cfg > output.ppm
```

## 🧠 What I learned

A lot of applied maths and clean OOP design in C++, plus a genuinely extensible
architecture — going from a blank page and equations to a real rendered image.

---

*Project built as part of the Epitech curriculum (OOP-400 module).*
