---
title: "项目"
permalink: /zh/projects/
locale: "zh-CN"
lang: zh-CN
---

### [Boyle](https://github.com/boyle-org/boyle) — 高性能 C++ 数值计算库

**自动驾驶与机器人学的基础数学库**

- 完全使用 **C++23** 标准实现，代码量超过两万行，大量运用现代模板元编程技术
- 以头文件为主的库，提供细粒度 CMake 目标——只链接你需要的模块
- **核心模块：**
  - `boyle::math` — 稠密/稀疏线性代数、分段曲线（线性/三次/五次样条）、FFT、切比雪夫多项式、SIMD 向量化（AVX-512）
  - `boyle::cvxopm` — 凸优化：QP 求解器（OSQP）、L-BFGS、BFGS、Nelder-Mead、线搜索
  - `boyle::kinetics` — 运动规划：路径/轨迹建模、三次/五次加速度与偏移模型（QP 优化）
  - `boyle::common` — 有限状态机、日志系统（基于 spdlog）、对齐分配器、RAII 工具
- CMake/xmake 双构建系统，支持多平台部署（Linux/macOS/Windows）
- 全自动化 GitHub Actions CI/CD 流水线，完整单元测试覆盖
- 许可证：BSD-3-Clause

---

### [LhcVaspTools](https://github.com/houchen-li/LhcVaspTools) — VASP 数据分析工具包

用于从 VASP 输出文件（vaspout.h5）读取数据并创建出版级质量图表的 Python 工具包。在 MPI-CPFS 研究期间开发，用于 DFT 计算结果的后处理。

---

### 开源贡献

- **Arch Linux** — 修复 bcachefs 安装镜像问题
- **xdit** — 将分布式推理框架移植到摩尔线程 GPU
- **long-context-attention** — 将长上下文注意力机制移植到摩尔线程 GPU
