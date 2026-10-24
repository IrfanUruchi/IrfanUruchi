
# Irfan Uruchi

**Computer Engineer** · Operating Systems · Scientific Computing · Machine Learning · Distributed Systems

I develop Linux software, scientific research tools, domain-specific language models, and distributed applications. My work covers both the software and the hardware it runs on, from desktop operating systems and GPU inference to Raspberry Pi deployments and custom processor designs.

<p align="left">
  <a href="https://irfanuruchi.in">
    <img src="https://img.shields.io/badge/Portfolio-111111?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio">
  </a>
  <a href="https://huggingface.co/Irfanuruchi">
    <img src="https://img.shields.io/badge/Hugging%20Face-111111?style=for-the-badge&logo=huggingface&logoColor=FFD21E" alt="Hugging Face">
  </a>
  <a href="https://hub.docker.com/u/irfanuruchi">
    <img src="https://img.shields.io/badge/Docker%20Hub-111111?style=for-the-badge&logo=docker&logoColor=2496ED" alt="Docker Hub">
  </a>
  <a href="https://apps.apple.com/rw/developer/irfan-uruci/id1761565214">
    <img src="https://img.shields.io/badge/App%20Store-111111?style=for-the-badge&logo=apple&logoColor=white" alt="App Store">
  </a>
</p>

---

## Selected projects

### IULinux — Linux distribution

An Ubuntu 26.04 LTS-based distribution using KDE Plasma, currently at **0.1 Alpha 1**.

- Custom Settings application built with Qt/QML and Python.
- App Store using AppStream metadata, PackageKit, and PolicyKit authorization.
- Signed APT updates and optional workstation profiles.
- Calamares installer integration, Debian packaging, filesystem overlays, and ISO builds.
- Release testing and documentation, including known hardware and Secure Boot limitations.

<p>
  <a href="https://iulinux-website.pages.dev">
    <img src="https://img.shields.io/badge/Official_Website-161B22?style=flat-square&logo=linux&logoColor=white" alt="IULinux website">
  </a>
  <a href="https://github.com/IrfanUruchi/IULinux">
    <img src="https://img.shields.io/badge/Source_Code-161B22?style=flat-square&logo=github&logoColor=white" alt="IULinux source">
  </a>
  <a href="https://iulinux-website.pages.dev/handbook.html">
    <img src="https://img.shields.io/badge/Technical_Handbook-161B22?style=flat-square&logo=readthedocs&logoColor=white" alt="Technical handbook">
  </a>
</p>

### ELENXIS — Scientific computing

A neuro-symbolic framework for investigating contradictions in scientific observations and evaluating candidate hypotheses. The implementation combines **Python, Haskell, Prolog, and Fortran**.

The research workflow includes simulation, anomaly and sensitivity analysis, calibration, experimental design, and reproducible evaluation runs with traceable results. The focus is on comparing hypotheses against evidence rather than treating generated explanations as conclusions.

<p>
  <a href="https://github.com/IrfanUruchi/ELENXIS">
    <img src="https://img.shields.io/badge/Repository_%26_Research-161B22?style=flat-square&logo=github&logoColor=white" alt="ELENXIS repository">
  </a>
</p>

### BuildEng — Model fine-tuning

Domain-specific language models for civil and structural engineering, HVAC, construction workflows, and field diagnostics. This work includes **dataset preparation and validation, fine-tuning, evaluation, model merging, quantization, and deployment**—not just inference with existing models.

- **BuildEng V8:** Qwen2.5-32B-Instruct fine-tuned using 4-bit QLoRA.
- **Training data:** 145,117 validated examples; 4,096-token sequences.
- **Model branches:** 1.5B, 3B, and 32B.
- **Deployment formats:** merged models, GGUF variants, MLX releases, and OpenVINO exports.
- **Additional work:** English–Albanian DSP fine-tuning, computer-engineering and networking models, HVAC prechecks, and compact edge models.

Across these projects, I have published **30+ model, adapter, conversion, and quantization releases**.

<p>
  <a href="https://huggingface.co/Irfanuruchi/buildeng">
    <img src="https://img.shields.io/badge/Training_Dataset-161B22?style=flat-square&logo=huggingface&logoColor=FFD21E" alt="BuildEng dataset">
  </a>
  <a href="https://huggingface.co/Irfanuruchi/qwen2.5-32b-buildeng-GGUF-F16">
    <img src="https://img.shields.io/badge/BuildEng_32B-161B22?style=flat-square&logo=huggingface&logoColor=FFD21E" alt="BuildEng 32B">
  </a>
  <a href="https://huggingface.co/Irfanuruchi/qwen2.5-3b-buildeng">
    <img src="https://img.shields.io/badge/BuildEng_3B-161B22?style=flat-square&logo=huggingface&logoColor=FFD21E" alt="BuildEng 3B">
  </a>
  <a href="https://huggingface.co/Irfanuruchi/qwen2.5-1.5b-buildeng">
    <img src="https://img.shields.io/badge/BuildEng_1.5B-161B22?style=flat-square&logo=huggingface&logoColor=FFD21E" alt="BuildEng 1.5B">
  </a>
</p>

---

## Distributed and edge systems

| Project | Implementation |
| --- | --- |
| **Distributed Task Orchestration** | FastAPI coordinator, gRPC/Protobuf workers, SQLite queue, heartbeats, retries, and capability-aware scheduling across Linux and macOS machines. |
| **Intelligent Fog Orchestration** | MQTT node telemetry, desired-state reconciliation, container monitoring, and automatic workload recovery. |
| [![PMDrop](https://img.shields.io/badge/PMDrop-161B22?style=flat-square&logo=github&logoColor=white)](https://github.com/IrfanUruchi/PMDrop) | Raspberry Pi-based local file transfer; FastAPI, SQLite, device registration, and ARM64/x86_64 Docker deployment. |
| [![Wireless Monitoring Network](https://img.shields.io/badge/Wireless_Monitoring_Network-161B22?style=flat-square&logo=github&logoColor=white)](https://github.com/IrfanUruchi/wmn-system) | RSSI, latency, jitter, and packet-loss monitoring; MQTT, offline telemetry spooling, alerts, and Grafana. |
| [![Edge Mini Cloud](https://img.shields.io/badge/Edge_Mini_Cloud-161B22?style=flat-square&logo=github&logoColor=white)](https://github.com/IrfanUruchi/Distributed-edge-mini-cloud-Docker) | Self-hosted environment with Nextcloud, Prometheus, Grafana, Jupyter, Samba, and local inference. |
| [![Adaptive IoT Gateway](https://img.shields.io/badge/Adaptive_IoT_Gateway-161B22?style=flat-square&logo=github&logoColor=white)](https://github.com/IrfanUruchi/Adaptive-IoT-Gateway) | Raspberry Pi, MQTT, device/network telemetry, and containerized services. |

## iOS applications

| Application | Scope |
| --- | --- |
| [![EngToolBox](https://img.shields.io/badge/EngToolBox-161B22?style=flat-square&logo=apple&logoColor=white)](https://github.com/IrfanUruchi/EngToolBox) | Engineering calculations, numerical and symbolic mathematics. |
| [![UnitEngConverter](https://img.shields.io/badge/UnitEngConverter-161B22?style=flat-square&logo=apple&logoColor=white)](https://github.com/IrfanUruchi/UnitEngConverter) | Engineering unit conversions. |
| [![Smart Study Planner](https://img.shields.io/badge/Smart_Study_Planner-161B22?style=flat-square&logo=apple&logoColor=white)](https://github.com/IrfanUruchi/Smart-Study-Planner) | Task planning, study scheduling, and timers. |
| [![PlayAIground](https://img.shields.io/badge/PlayAIground-161B22?style=flat-square&logo=apple&logoColor=white)](https://github.com/IrfanUruchi/PlayAIground) | On-device language-model experiments on iOS. |

<details>
<summary><strong>Additional projects — databases, embedded systems, and programming languages</strong></summary>

### Data and backend

- [![Real-Time Price Alert](https://img.shields.io/badge/Real--Time_Price_Alert-161B22?style=flat-square&logo=github&logoColor=white)](https://github.com/IrfanUruchi/realtime-price-alert-system) — Event-driven stock-price monitoring, price-drop detection, automated alerts, and containerized services.
- [![ProMatch](https://img.shields.io/badge/ProMatch-161B22?style=flat-square&logo=github&logoColor=white)](https://github.com/IrfanUruchi/promatch-prolog) — SWI-Prolog matchmaking with greedy scheduling and CLP(FD).
- **Local LLM Service** — Docker-based GGUF inference interface with configurable models and persistent SQLite conversations.
- **NoSQL Retail Migration** — PostgreSQL 16 to MongoDB 7; validation of 99,441 orders, 32,951 products, and 96,096 customers, with a Streamlit analytics dashboard.

### Embedded systems and architecture

- [![ALPR Gate](https://img.shields.io/badge/ALPR_Gate-161B22?style=flat-square&logo=github&logoColor=white)](https://github.com/IrfanUruchi/automated-license-plate-gate-control) — YOLOv8 Nano and EasyOCR on Raspberry Pi with Arduino gate control.
- **Processor design** — Custom 8-bit and Z80-style CPUs, ALU/datapath/control logic, Logisim, Verilog, and FPGA experiments.

### Language and model tooling

- [![Haskell Calculator](https://img.shields.io/badge/Haskell_Symbolic_Calculator-161B22?style=flat-square&logo=github&logoColor=white)](https://github.com/IrfanUruchi/Haskell-Integral-Derivative-Calculator) — Recursive-descent parsing, simplification, symbolic differentiation, and integration.
- [![Bilingual DSP LLM](https://img.shields.io/badge/Bilingual_DSP_LLM-161B22?style=flat-square&logo=github&logoColor=white)](https://github.com/IrfanUruchi/dsp-llm-bilingual-finetuning) — English–Albanian digital signal-processing dataset and fine-tuning pipeline.
- [![LLM Box](https://img.shields.io/badge/LLM_Box-161B22?style=flat-square&logo=github&logoColor=white)](https://github.com/IrfanUruchi/llm-docker-app) — FastAPI/Docker model-serving interface.

</details>

---

## Technical stack

| Area | Technologies |
| --- | --- |
| **Languages** | Python, C/C++, Swift, Kotlin, Assembly, Verilog, Haskell, Prolog, Fortran, SQL |
| **ML training and inference** | PyTorch, Transformers, LoRA/QLoRA, Hugging Face, CUDA, MLX, GGUF, llama.cpp, OpenVINO, Core ML |
| **Operating systems and infrastructure** | Linux, Qt/QML, Debian packaging, Docker, Proxmox, Prometheus, Grafana |
| **Distributed systems and data** | FastAPI, gRPC, Protobuf, MQTT, WebRTC, SQLite, PostgreSQL, MongoDB |
| **Embedded and mobile** | Raspberry Pi, Arduino, FPGA, SwiftUI, Jetpack Compose |

---

B.Sc. in Computer Engineering · South East European University · 2026 (240 ECTS)

| Project | Implementation |
| --- | --- |
| Distributed Task Orchestration | FastAPI coordinator, gRPC/Protobuf workers, SQLite queue, heartbeats, retries, and capability-aware scheduling across Linux and macOS machines. |
| Intelligent Fog Orchestration | MQTT node telemetry, desired-state reconciliation, container monitoring, and automatic workload recovery. |
| [PMDrop](https://github.com/IrfanUruchi/PMDrop) | Raspberry Pi-based local file transfer; FastAPI, SQLite, device registration, and ARM64/x86_64 Docker deployment. |
| [Wireless Monitoring Network](https://github.com/IrfanUruchi/wmn-system) | RSSI, latency, jitter, and packet-loss monitoring; MQTT, offline telemetry spooling, alerts, and Grafana. |
| [Edge Mini Cloud](https://github.com/IrfanUruchi/Distributed-edge-mini-cloud-Docker) | Self-hosted environment with Nextcloud, Prometheus, Grafana, Jupyter, Samba, and local inference. |
| [Adaptive IoT Gateway](https://github.com/IrfanUruchi/Adaptive-IoT-Gateway) | Raspberry Pi, MQTT, device/network telemetry, and containerized services. |

## iOS applications

| Application | Scope |
| --- | --- |
| [EngToolBox](https://github.com/IrfanUruchi/EngToolBox) | Engineering calculations, numerical and symbolic mathematics. |
| [UnitEngConverter](https://github.com/IrfanUruchi/UnitEngConverter) | Engineering unit conversions. |
| [Smart Study Planner](https://github.com/IrfanUruchi/Smart-Study-Planner) | Task planning, study scheduling, and timers. |
| [PlayAIground](https://github.com/IrfanUruchi/PlayAIground) | On-device language-model experiments on iOS. |

<details>
<summary><strong>Additional projects — databases, embedded systems, and programming languages</strong></summary>

### Data and backend

- [Real-Time Price Alert System](https://github.com/IrfanUruchi/realtime-price-alert-system): Event-driven stock-price monitoring, price-drop detection, automated alerts, and containerized services.
- [ProMatch](https://github.com/IrfanUruchi/promatch-prolog): SWI-Prolog matchmaking with greedy scheduling and CLP(FD).
- **Local LLM Service:** Docker-based GGUF inference interface with configurable models and persistent SQLite conversations.
- **NoSQL Retail Migration:** PostgreSQL 16 to MongoDB 7; validation of 99,441 orders, 32,951 products, and 96,096 customers, with a Streamlit analytics dashboard.

### Embedded systems and architecture

- [ALPR Gate](https://github.com/IrfanUruchi/automated-license-plate-gate-control): YOLOv8 Nano and EasyOCR on Raspberry Pi with Arduino gate control.
- **Processor design:** custom 8-bit and Z80-style CPUs, ALU/datapath/control logic, Logisim, Verilog, and FPGA experiments.

### Language and model tooling

- [Haskell Symbolic Calculator](https://github.com/IrfanUruchi/Haskell-Integral-Derivative-Calculator): recursive-descent parsing, simplification, symbolic differentiation, and integration.
- [Bilingual DSP LLM](https://github.com/IrfanUruchi/dsp-llm-bilingual-finetuning): English–Albanian digital signal-processing dataset and fine-tuning pipeline.
- [LLM Box](https://github.com/IrfanUruchi/llm-docker-app): FastAPI/Docker model-serving interface.

</details>

---

## Technical stack

| Area | Technologies |
| --- | --- |
| Languages | Python, C/C++, Swift, Kotlin, Assembly, Verilog, Haskell, Prolog, Fortran, SQL |
| ML training and inference | PyTorch, Transformers, LoRA/QLoRA, Hugging Face, CUDA, MLX, GGUF, llama.cpp, OpenVINO, Core ML |
| Operating systems and infrastructure | Linux, Qt/QML, Debian packaging, Docker, Proxmox, Prometheus, Grafana |
| Distributed systems and data | FastAPI, gRPC, Protobuf, MQTT, WebRTC, SQLite, PostgreSQL, MongoDB |
| Embedded and mobile | Raspberry Pi, Arduino, FPGA, SwiftUI, Jetpack Compose |

B.Sc. in Computer Engineering · South East European University · 2026 (240 ECTS)
