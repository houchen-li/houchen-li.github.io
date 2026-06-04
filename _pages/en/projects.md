---
title: "Projects"
permalink: /en/projects/
---

### [Boyle](https://github.com/boyle-org/boyle) — High-Performance C++ Numerical Computing Library

**The Mathematical Foundation for Autonomous Vehicles and Robotics**

- Implemented entirely in **C++23** with 20,000+ lines of code, extensively leveraging modern template metaprogramming
- Primarily header-based library with fine-grained CMake targets — link only what you need
- **Core Modules:**
  - `boyle::math` — Dense/sparse linear algebra, piecewise curves (linear/cubic/quintic splines), FFT, Chebyshev polynomials, SIMD vectorization (AVX-512)
  - `boyle::cvxopm` — Convex optimization: QP solver (OSQP), L-BFGS, BFGS, Nelder-Mead, line search
  - `boyle::kinetics` — Motion planning: route/path/motion modeling, cubic/quintic acceleration & offset models via QP optimization
  - `boyle::common` — FSM, logging (spdlog-based), aligned allocators, RAII utilities
- Dual build systems (CMake + xmake), cross-platform (Linux/macOS/Windows)
- Fully automated GitHub Actions CI/CD with comprehensive unit test coverage
- License: BSD-3-Clause

---

### [LhcVaspTools](https://github.com/houchen-li/LhcVaspTools) — VASP Data Analysis Toolkit

Python toolkit for reading data from VASP output files (vaspout.h5) and creating publication-quality plots. Developed during research at MPI-CPFS for post-processing DFT calculation results.

---

### Open Source Contributions

- **Arch Linux** — Fixed bcachefs installation image issue
- **xdit** — Ported distributed inference framework to Moore Threads GPU
- **long-context-attention** — Ported long-context attention mechanism to Moore Threads GPU
