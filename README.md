# 2D Pixel Interpolation — Numerical Methods Project

**Course:** Numerical Methods (iMAT) — 2023/24  
**Project:** Integrative Project — 2D Pixel Interpolation  
**Authors:** Ana Rodríguez · Blanca López-Jorrín · Jorge Ibinarriaga · Miguel Ángel Huamani · Victoria Guillén  

---

## 🧠 Overview

This project explores **2D interpolation techniques** and their application to **digital image processing**, particularly for image **scaling and resampling**.  
It was developed as part of the *Numerical Methods* course (Universidad Pontificia Comillas, ICAI).

The work is implemented in a single MATLAB Live Script:

```
interpolation_2d.mlx
```

This file contains the **explanations**, **mathematical derivations**, and **MATLAB implementations** of the interpolation methods.

---

## 🔬 Methods Implemented

The following interpolation algorithms are implemented and compared:

- **Nearest Neighbor Interpolation**
- **Bilinear Interpolation**
- **Bicubic Interpolation**
- **Voronoi Diagrams** for nearest-neighbor visualization

Each method is applied to both:
- Analytic functions (e.g., \( f(x, y) = \sin(2x)(x^2 - xy + y^2) \))
- Real images (to compare visual quality and smoothness)

---

## 🎯 Learning Objectives

- Understand the theory behind **2D interpolation methods**.  
- Implement these methods in **MATLAB**.  
- Apply them to **image scaling, rotation, and enhancement**.  
- Compare the performance and quality of each method.

---

## ⚙️ How to Run

1. Open the file `interpolation_2d.mlx` in **MATLAB**.  
2. Run the sections sequentially or execute the entire file (`Run All`).  
3. The script will:
   - Explain the mathematical background.
   - Show code implementations.
   - Display comparative results with figures.

---

## 📚 References

- Hudson, S. — *Lecture 16: Interpolation in 2D*  
- Burger, W. & Burge, M. — *Principles of Digital Image Processing* (Springer, 2009, 2013)  
- Keys, R. G. — *Cubic Convolution Interpolation for Digital Image Processing*  
- Alba Roncero García — *TFG Universitat Jaume I*  

---

## 🖼️ Example Output

The script produces visual comparisons between interpolation techniques on both **functions** and **images**, illustrating differences in smoothness, resolution, and edge preservation.

---

## 📁 Repository Contents

```
.
├── interpolation_2d.mlx   # Main MATLAB Live Script (all code and explanations)
└── README.md              # Project documentation
```

---

### 💡 Summary

This project integrates numerical interpolation concepts with real-world applications in **image processing**, demonstrating how mathematical methods can enhance digital images through scaling, rotation, and reconstruction.
