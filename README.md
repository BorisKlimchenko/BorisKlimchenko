<div align="center">
  <img src="https://github.com/BorisKlimchenko.png" width="180">
  
  <h1>Boris Klimchenko</h1>
  
  <h3>🚀 ML Systems Engineer | Generative AI Specialist</h3>

  <p>
    <b>Core Focus:</b><br>
    High-Performance Inference • Latent Diffusion Pipelines • Modular Software Architecture
  </p>

  <a href="https://www.youtube.com/channel/UC_wq5ASqVRPkqu_P1iTk_tA">
    <img src="https://img.shields.io/badge/YouTube-Dev_Logs-red?style=for-the-badge&logo=youtube&logoColor=white">
  </a>
</div>

<br>

### 📡 Current Status
> *"The map is not the territory. The token is not the meaning."* — Alfred Korzybski

* **Role:** Developing hardware-aware inference engines for Open Source models.
* **Objective:** Bridging the gap between experimental Research code and Production-grade engineering.
* **Active Sprint:** Implementing **Adaptive Hardware Strategy** (HAL) & **Deterministic Sampling** for Latent Diffusion pipelines.

---

### 🛠️ Engineering Stack

| **Domain** | **Stack & Instrumentation** |
| :--- | :--- |
| **Deep Learning** | ![Python](https://img.shields.io/badge/Python-3.10+-3776AB?logo=python&logoColor=white) ![PyTorch](https://img.shields.io/badge/PyTorch-2.0+-EE4C2C?logo=pytorch&logoColor=white) ![Diffusers](https://img.shields.io/badge/🤗_Diffusers-v0.25+-FFD21E?logo=huggingface&logoColor=black) ![xFormers](https://img.shields.io/badge/Meta-xFormers-blue) |
| **Generative R&D** | ![AnimateDiff](https://img.shields.io/badge/Model-AnimateDiff-orange) ![ControlNet](https://img.shields.io/badge/CV-ControlNet-4682B4) ![Stable Diffusion](https://img.shields.io/badge/SD-v1.5%2FXL-4B0082) ![Optimization](https://img.shields.io/badge/Task-Inference_Opt-green) |
| **Infrastructure** | ![Linux](https://img.shields.io/badge/Linux-Bash-FCC624?logo=linux&logoColor=black) ![Docker](https://img.shields.io/badge/Docker-Container-2496ED?logo=docker&logoColor=white) ![CUDA](https://img.shields.io/badge/NVIDIA-CUDA_Profiling-76B900?logo=nvidia&logoColor=white) ![Colab](https://img.shields.io/badge/Google-Colab_Pro-F9AB00?logo=googlecolab&logoColor=white) |
| **Architecture** | ![OOP](https://img.shields.io/badge/Pattern-OOP-lightgrey) ![SOLID](https://img.shields.io/badge/Principle-SOLID-lightgrey) ![Strategy](https://img.shields.io/badge/Design-Strategy_Pattern-9cf) ![Clean Arch](https://img.shields.io/badge/Arch-Clean_Code-success) |
---

### 🧬 Featured Project: <a href="https://github.com/BorisKlimchenko/JEPA-Synthetic-Lab">Adaptive-Motion-Lab</a>

**Status:** v1.0 Stable (Refactored)  
**Type:** Hardware-Aware Inference Engine for AnimateDiff.  
**Engineering Challenge:** Solving the "works on my machine" problem for heavy diffusion models across heterogeneous hardware (T4 vs A100).

**Key Implementation Details:**
* **Hardware Abstraction Layer (HAL):** Runtime detection of GPU Architecture (Ampere vs Turing).
* **Strategy Pattern:** Dynamic injection of Attention mechanisms (Native SDPA vs Memory Efficient xFormers).
* **VRAM Safety:** Automatic resolution scaling and CPU-offload based on available memory.

---

<div align="center">
  <p><i>Building tools for the next generation of synthetic media.</i></p>
</div>
