# Alex Jo

| [KR 한국어](../../README.md) | [US English](./en.md) | [JP 日本語](./ja.md) | [CN 简体中文](./zh-CN.md) | [ES Español](./es.md) |
| :---: | :---: | :---: | :---: | :---: |
| [FR Français](./fr.md) | [DE Deutsch](./de.md) | [RU Русский](./ru.md) | [SA العربية](./ar.md) | [IN हिन्दी](./hi.md) |

---

### Systems & Security Engineering

专注于确定性低层运行时、二进制分析工具链、内存安全执行环境以及本地 AI 推理加速内核的系统与安全工程师。倡导消除冗余抽象，追求第一性原理架构与可重现构建（Reproducible Builds）。

---

### 核心研究与架构原则

- **确定性执行 (Deterministic Execution)**: 确保编译器、工具链和运行时环境跨平台实现比特级绝对一致的可重现性。
- **内存安全与运行时完整性 (Memory Safety & Runtime Integrity)**: 深度审计原生边界，实施基于能力的内存模型与执行面隔离。
- **超低开销高性能计算 (Low-Overhead HPC)**: 采用 SIMD/AVX 向量化计算与缓存友好的内存布局，释放硬件极限性能。
- **取证逆向工程与静态分析 (Forensic Reverse Engineering)**: 构建高保真反编译流水线、静态分析不变量验证与行为语义确定性审计。
- **边缘推理加速 (Edge Inference Acceleration)**: 优化量化算法（GGUF、AWQ、EXL2）与计算图，最大化受限硬件资源利用率。

---

### 核心技术矩阵

| 领域 | 核心技术栈与工具链 |
| :--- | :--- |
| **系统与底层开发** | C, C++, Rust, Go, x86_64 / ARM64 Assembly, Linux Kernel / Windows NT Internals |
| **逆向工程与安全审计** | Ghidra, IDA Pro, x64dbg, Binary Ninja, Frida, LLVM / Clang AST Tooling |
| **推理与硬件加速** | CUDA, llama.cpp / GGUF, TensorRT, Triton, OpenVINO, ONNX Runtime |
| **分布式与云原生** | Linux eBPF, Docker, POSIX Runtimes, High-Throughput gRPC / Protocol Buffers |
| **存储与高并发** | Zero-Copy I/O, Lock-Free Ring Buffers, LSM Trees, Memory-Mapped Persistence |

---

### 平台索引

- **GitHub**: [github.com/i-AI-helper](https://github.com/i-AI-helper) — 主开源代码库、系统运行时与工程技术规范
- **GitLab**: [gitlab.com/jo060235355](https://gitlab.com/jo060235355) — 自动化 CI/CD 流水线与交叉验证镜像
- **Hugging Face**: [huggingface.co/kfoikeom](https://huggingface.co/kfoikeom) — 模型量化权重、基准评测数据集与推理内核

---

### 工程哲学

> “复杂性是安全与正确性最大的敌人。真正的工程优雅，在于剔除多余抽象，用第一性原理证明确定性行为。”
