<p align="center">
  <img src="https://img.shields.io/badge/StarRobotics-Open%20Source%20Embodied%20Intelligence-blue?style=for-the-badge" alt="StarRobotics"/>
</p>

<h1 align="center">⭐ StarRobotics</h1>

<p align="center">
  <b>High-Quality Open-Source Codebases for Embodied Intelligence</b>
</p>

<p align="center">
  <a href="https://github.com/StarRobotics"><img src="https://img.shields.io/badge/GitHub-StarRobotics-181717?logo=github" alt="GitHub"/></a>
  <a href="https://huggingface.co/StarRobotics"><img src="https://img.shields.io/badge/HuggingFace-Models%20%26%20Data-orange?logo=huggingface" alt="HuggingFace"/></a>
  <a href="#community"><img src="https://img.shields.io/badge/WeChat-Join%20Us-brightgreen?logo=wechat" alt="WeChat"/></a>
</p>

---

## 🎯 Mission

**StarRobotics** is an open-source organization dedicated to advancing embodied intelligence through modular, production-quality codebases. We believe the future of robotics lies in open collaboration — every component, from perception to action, should be transparent, reproducible, and easy to build upon.

> *"Making embodied intelligence development as easy as building with Lego blocks."*

---

## 🏗️ Repository Map

| Repository | Focus | Status | Description |
|:---:|:---:|:---:|:---|
| [**StarVLA**](https://github.com/StarRobotics/StarVLA) | Vision-Language-Action | ✅ Active | Lego-like codebase for VLA model developing. Supports Qwen-FAST, Qwen-OFT, Qwen-PI, Qwen-GR00T and more. |
| [**StarWA**](https://github.com/StarRobotics/StarWA) | World-Action Model | 🚧 In Progress | World model–driven action prediction. Combines visual world simulation with embodied action planning. |
| [**StarBot**](https://github.com/StarRobotics/StarBot) | Generic Embodied Robot | 🚧 In Progress | Unified robot control stack for diverse embodiments — manipulation, locomotion, and beyond. |

```
StarRobotics/
├── StarVLA       # VLA: vision + language → action
├── StarWA        # WA:  world model → action planning
└── StarBot       # Bot: generic embodied robot platform
```

---

## ⭐ StarVLA — Vision-Language-Action Models

> *A Lego-like Codebase for Vision-Language-Action Model Developing*

StarVLA provides a modular framework for developing VLA models with plug-and-play components. Each functional module (model, data, trainer, config, evaluation) follows **high cohesion & low coupling** principles.

**Highlights:**
- 4 VLA frameworks: Qwen-FAST, Qwen-OFT, Qwen-PI, Qwen-GR00T
- Multiple VLM backbones: Qwen2.5-VL, Qwen3-VL, Florence-2
- Benchmark support: SimplerEnv, LIBERO, RoboCasa, and more
- VLM co-training for multimodal multitask learning
- DeepSpeed ZeRO-2/3 & multi-node training
- Stand up a new VLA framework in **< 3 hours**

📦 [GitHub](https://github.com/StarRobotics/StarVLA) · 🤗 [Models & Data](https://huggingface.co/StarVLA)

---

## 🌍 StarWA — World-Action Models

> *Learning to Act through World Simulation*

StarWA focuses on **world model–driven action prediction**: learning a predictive model of the environment and leveraging it for embodied decision-making. By combining visual world simulation with action planning, StarWA enables robots to reason about consequences before acting.

**Planned Features:**
- Video prediction / visual world models
- Latent dynamics learning
- Action planning via model-based rollouts
- Integration with StarVLA for hybrid VLA + WA pipelines
- Sim-to-real transfer utilities

📦 *Coming Soon*

---

## 🤖 StarBot — Generic Embodied Robot Platform

> *One Stack, Every Robot*

StarBot aims to be a unified, robot-agnostic control stack that supports diverse embodiments — from tabletop manipulators to humanoids and mobile platforms.

**Planned Features:**
- Generic robot interface abstraction
- Multi-embodiment configuration system
- Real-world deployment utilities (policy server, safety layers)
- Cross-embodiment transfer tools
- Hardware drivers & calibration for common platforms

📦 *Coming Soon*

---

## 🗺️ Roadmap

### 2025
- [x] StarVLA v1: core VLA framework release
- [x] 4 VLA architectures (FAST, OFT, PI, GR00T)
- [x] SimplerEnv & LIBERO & Robocasa-GR1 & Robotwin 2.0 evaluation
- [x] VLM co-training support


### 2026
- [ ] StarVLA v2: expanded benchmarks & new architectures
- [ ] StarWA v0: initial world-action model codebase
- [ ] StarBot v0: generic robot platform prototype
- [ ] Cross-repo integration (VLA ↔ WA pipelines)
- [ ] Real-world deployment toolkit

### Long-term
- [ ] Foundation model for general-purpose embodied agents
- [ ] Community benchmark & leaderboard
- [ ] Sim-to-real bridge across all repos

---

## 🧬 Design Philosophy

All StarRobotics codebases share a common set of principles:

| Principle | Description |
|:---|:---|
| **Modular (Lego-like)** | Every component is self-contained and independently testable. |
| **Explicit Boundaries** | Clear interfaces between data, model, and training — no hidden coupling. |
| **Flat Configuration** | Single config entry point; override anything from CLI. |
| **Reproducible** | Pin versions, publish checkpoints, ship evaluation scripts. |
| **Community-first** | MIT-licensed, open roadmap, weekly office hours. |

---

## 🤝 How to Contribute

We welcome contributions across all repos:

1. **Report bugs** — Open an Issue with a minimal repro.
2. **Propose features** — Start a Discussion or fill out the [Cooperation Form](https://forms.gle/R4VvgiVveULibTCCA).
3. **Submit PRs** — Align scope via an Issue first, then `make check` before submitting.
4. **Join office hours** — Every Friday afternoon for live discussion.

---

<a id="community"></a>

## 💬 Community

| Channel | Link |
|:---|:---|
| GitHub Org | [github.com/StarRobotics](https://github.com/StarRobotics) |
| HuggingFace | [huggingface.co/StarVLA](https://huggingface.co/StarVLA) |
| WeChat Group | Scan the QR code in the StarVLA repo |
| Cooperation Form | [Google Form](https://forms.gle/R4VvgiVveULibTCCA) |

---

## ✍️ Citation

```bibtex
@misc{starrobotics2025,
  title  = {StarRobotics: High-Quality Open-Source Codebases for Embodied Intelligence},
  author = {StarRobotics Community},
  url    = {https://github.com/StarRobotics},
  year   = {2025}
}

@misc{starvla2025,
  title  = {StarVLA: A Lego-like Codebase for Vision-Language-Action Model Developing},
  author = {StarVLA Community},
  url    = {https://github.com/StarRobotics/StarVLA},
  year   = {2025}
}
```

---

## 📄 License

All StarRobotics projects are released under the **MIT License** — free for commercial use, modification, and distribution.

---

<p align="center">
  <b>⭐ Star us on GitHub to stay updated!</b><br>
  <i>Building the open-source infrastructure for embodied intelligence, one repo at a time.</i>
</p>
