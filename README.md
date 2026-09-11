<div align="center">

```
  ██╗      █████╗ ██╗  ██╗███████╗██╗  ██╗██╗   ██╗███████╗███╗   ██╗██████╗ 
  ██║     ██╔══██╗██║ ██╔╝██╔════╝██║  ██║╚██╗ ██╔╝██╔════╝████╗  ██║██╔══██╗
  ██║     ███████║█████═╝ ███████╗███████║ ╚████╔╝ █████╗  ██╔██╗ ██║██║  ██║
  ██║     ██╔══██║██╔═██╗ ╚════██║██╔══██║  ╚██╔╝  ██╔══╝  ██║╚██╗██║██║  ██║
  ███████╗██║  ██║██║  ██╗███████║██║  ██║   ██║   ███████╗██║ ╚████║██████╔╝
  ╚══════╝╚═╝  ╚═╝╚═╝  ╚═╝╚══════╝╚═╝  ╚═╝   ╚═╝   ╚══════╝╚═╝  ╚═══╝╚═════╝ 
```

### ⚡ Systems Architecture • Compiler Toolchains • OS Sandboxing ⚡

[![Vercel Deployment](https://img.shields.io/badge/Vercel-Live%20Production-00f2fe?style=for-the-badge&logo=vercel&logoColor=black)](https://portfolio-three-chi-k49n3rk66u.vercel.app)
[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-2ea44f?style=for-the-badge&logo=github&logoColor=white)](https://laksh1357.github.io/Portfolio/)
[![Academic Standing](https://img.shields.io/badge/VIT%20Vellore-9.52%20CGPA-FFD700?style=for-the-badge&logo=google-scholar&logoColor=black)](https://www.linkedin.com/in/lakshya-singh-579175277)
[![LeetCode](https://img.shields.io/badge/LeetCode-@lakshya__03__-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/u/lakshya_03_/)

---

<p align="center">
  <b>Engineering at the Hardware-Software Boundary.</b><br>
  Interactive cyberpunk terminal portfolio featuring live diagnostic CLI, project filtering system, real-time toast notifications, and modular architecture.
</p>

[🌐 Explore Live Site](https://portfolio-three-chi-k49n3rk66u.vercel.app) • [💼 LinkedIn](https://www.linkedin.com/in/lakshya-singh-579175277) • [📬 Contact Me](mailto:singhlakshya7777@gmail.com)

</div>

---

## 🛰️ Overview

This repository contains the production source code for **Lakshya Singh**'s personal engineering website. Built with zero runtime JavaScript framework dependencies, utilizing **HTML5, CSS3, Tailwind CSS CDN**, and **Vanilla JavaScript**. 

Designed with a high-performance system terminal aesthetic (`warden_daemon`), dark glassmorphism styling (`.spec-card`), interactive diagnostic CLI prompt, project tag filtering, and dual-engine email dispatch (Formspree API + native `mailto:` fallback).

---

## 💡 Key Features & Interactive Architecture

### 🖥️ 1. Live Interactive CLI Terminal (`warden_daemon`)
- Integrated in the hero section for an immersive developer experience.
- Supports interactive commands:
  - `cat /proc/sys/kernel/identity`: Displays academic, departmental, and engineering stats.
  - `check-subsystems`: Runs real-time verification status across Warden, Sudarshan, and RAG pipelines.
  - `ls projects`: Lists featured production repositories.
  - `fetch leetcode`: Fetches algorithmic problem-solving profile highlights.
  - `contact`: Instantly jumps to the communication endpoints section.
  - `clear`: Wipes the terminal buffer.

### 🏷️ 2. Dynamic Project Filtering Engine
- Real-time client-side DOM filtering by category:
  - `All (6)`: Full repository showcase.
  - `Systems`: Linux kernel sandboxes & networking scanners.
  - `Compilers`: 5-pass LL(1) recursive descent parsers & TAC virtual machines.
  - `AI / RAG`: Distributed BM25 + Dense vector search with Reciprocal Rank Fusion.
  - `Web Demos`: High-precision Canvas coordinate collision games.

### 🔔 3. Toast Feedback & Hardware-Accelerated Animations
- Custom notification toast triggered on copying emails or triggering API dispatches.
- `IntersectionObserver`-backed `fade-in-up` hardware-accelerated scroll animations.
- Dynamic `ScrollSpy` active link indicators in the fixed glassmorphism navigation header.

---

## 🛠️ Tech Stack & Badges

| Domain | Technologies Used |
| :--- | :--- |
| **Frontend Core** | ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) |
| **Styling & Icons** | ![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white) ![FontAwesome](https://img.shields.io/badge/Font_Awesome-339AF0?style=flat-square&logo=fontawesome&logoColor=white) |
| **Typography** | ![Google Fonts](https://img.shields.io/badge/Inter_&_JetBrains_Mono-4285F4?style=flat-square&logo=google&logoColor=white) |
| **Deployment & Hosting** | ![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white) ![GitHub Pages](https://img.shields.io/badge/GitHub_Pages-222222?style=flat-square&logo=github&logoColor=white) |

---

## 📦 Featured Systems Repositories Highlighted

| Project | Description | Stack | Link |
| :--- | :--- | :--- | :--- |
| **🛡️ Warden** | OS-level kernel sandbox isolating AI code with 5-layer security (seccomp-bpf, namespaces, cgroups v2, OverlayFS, DoD 5220.22-M memory zeroing). | `Linux Kernel` `Seccomp-BPF` `Node.js` `PostgreSQL` | [View Repo](https://github.com/laksh1357/OS_REPOSITORY.git) |
| **⚙️ Sudarshan** | 5-phase compiler pipeline in pure Python 3 (LL(1) recursive descent parser, AST, TAC quadruples, constant folding, and TAC VM). | `Python 3` `TAC IR` `Compiler Design` `VM` | [View Repo](https://github.com/laksh1357/MyOWN_Compiler.git) |
| **🔍 Enterprise RAG** | Production RAG search scaffold combining BM25 sparse + dense vector embeddings via Reciprocal Rank Fusion (RRF) and Cross-Encoders. | `FastAPI` `Hybrid RAG` `Docker` `Kubernetes` | [View Repo](https://github.com/laksh1357/AI_PROJECT.git) |
| **📡 LAN Watchtower** | Network telemetry scanner with multi-threaded ARP/ICMP sweeps, TCP port probing, SQLite WAL history, and desktop notifications. | `Python` `CustomTkinter` `Scapy` `SQLite` | [View Repo](https://github.com/laksh1357/NetworkMonitoring_DeviceDiscovery_Tool.git) |

---

## 🚀 Quick Start & Local Preview

Clone the repository and launch a simple HTTP server locally:

```bash
# Clone the repository
git clone https://github.com/laksh1357/Portfolio.git
cd Portfolio

# Option 1: Python HTTP Server
python3 -m http.server 3000

# Option 2: Node npx serve
npx serve .
```

Open your browser and navigate to `http://localhost:3000`.

---

## 📁 Workspace Directory Structure

```
portfolio/
├── index.html        # Main production HTML single-page application
├── README.md         # Comprehensive engineering documentation
└── .git/             # Version control metadata
```

---

## 📬 Contact & Links

- **Email**: [singhlakshya7777@gmail.com](mailto:singhlakshya7777@gmail.com)
- **GitHub**: [@laksh1357](https://github.com/laksh1357)
- **LeetCode**: [@lakshya_03_](https://leetcode.com/u/lakshya_03_/)
- **LinkedIn**: [lakshya-singh-579175277](https://www.linkedin.com/in/lakshya-singh-579175277)
- **Instagram**: [@laksh.ya_03_](https://www.instagram.com/laksh.ya_03_)

---

<div align="center">
  <sub>Developed & Maintained by <b>Lakshya Singh</b> • VIT Vellore (2024-2028)</sub>
</div>
