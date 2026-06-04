---
title: "Experience"
permalink: /en/experience/
---

### Infrastructure Engineer
**Beijing Tranxmart Technology Co., Ltd.** | Beijing, China | Dec. 2025 – Present

- Customized Linux kernel for NVIDIA Drive Orin platform: selectively configured kernel modules (virtualization, real-time mechanisms, etc.), completed kernel compilation and system image packaging
- Designed and implemented an autonomous driving Minimum Risk Condition (MRC) system compliant with ISO 26262 functional safety standards
- Deployed L4-level MRC on ultra-low-compute embedded chip TC397 using pure rule-based code, covering the full perception-planning-control-localization pipeline for safe pull-over maneuvers and emergency braking

---

### Senior AI Infrastructure Engineer
**Moore Threads Intelligent Technology Co., Ltd.** | Beijing, China | Apr. 2025 – Oct. 2025

- Developed fused operators and distributed data sharding strategies for Alibaba's Wan2.1/Wan2.2 video generation models on Moore Threads GPUs, reducing single inference latency to one-quarter of baseline
- Adapted the RoPE operator for Moore Threads hardware, which lacks native complex arithmetic support; decomposed complex rotary position encoding into equivalent floating-point operations to leverage the hardware's FP acceleration units
- Ported open-source inference frameworks xdit and long-context-attention to Moore Threads by replacing cuDNN SDPA with muDNN SDPA implementation
- Conducted a feasibility study on porting CUTLASS core operators by analyzing architectural differences between CUDA PTX and MUSA instruction sets

---

### Convex Optimization Algorithm Engineer
**Shenzhen Poisson Software Technology Co., Ltd.** | Beijing, China | Jun. 2024 – Feb. 2025

- Implemented L-BFGS quasi-Newton optimizer in C++17 with polymorphic memory allocators (PMR) and template compilation mechanisms, significantly reducing memory overhead and improving runtime performance
- Built a dense linear algebra library in C++17 covering LU/QR decomposition, matrix arithmetic, and SIMD vectorized multi-issue optimization
- Modernized the open-source pocketfft library to interface with STL generic containers, reducing integration complexity

---

### Planning & Control Algorithm Engineer
**Beijing Phigent Technology Co., Ltd.** | Beijing, China | Jun. 2023 – Jun. 2024

- Invented a quintic spline interpolation algorithm (C4 smoothness, O(n) complexity) with a dedicated sparse matrix solver, significantly improving motion control precision on high-curvature roads
- Designed and implemented dynamically expandable sparse matrix libraries (CscMatrix/CsrMatrix/CooMatrix/LilMatrix) providing efficient data structures for large-scale convex optimization formulation
- Proposed a Workspace+Task architectural design decoupling mathematical algorithms from business logic, enabling modular refactoring of the planning & control system

---

### Software Engineer
**Beijing Qingtian Truck Technology Co., Ltd.** | Beijing, China | Jul. 2022 – Jun. 2023

- Developed specialized sparse matrix solvers to improve matrix inversion efficiency
- Introduced higher-order boundary condition control to enhance trajectory smoothness
- Conducted Linux-based C++ development using the Bazel build system and Docker containerized deployment
