# 🧠 LLM Research Engineer Roadmap v3

> **From zero to research lab — your complete 38-week path to becoming an LLM Research Engineer at Anthropic, OpenAI, or Google DeepMind.**

**Author:** [Pratik Gade](https://github.com/ai-pratik) · **License:** MIT · **Open Source** 🌍

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Last Updated](https://img.shields.io/badge/Last%20Updated-March%202026-brightgreen)]()
[![Papers](https://img.shields.io/badge/Papers-55%2B-purple)]()
[![Weeks](https://img.shields.io/badge/Weeks-44%2B-orange)]()
[![Hours](https://img.shields.io/badge/Hours-~920-red)]()
[![Author](https://img.shields.io/badge/Author-Pratik%20Gade-blueviolet)]()

---

## 🚀 What Is This?

A **comprehensive, interactive, self-study curriculum** designed to take you from foundational AI/ML knowledge to research engineer readiness at top AI labs. Built as a single-page web application with:

- 📚 **55+ curated research papers** (12 marked as print-worthy)
- 🔨 **Step-by-step build tasks** with time estimates, difficulty levels, and expected outputs
- ✅ **Progress tracking** that saves automatically to your browser
- 🎯 **3 specialization tracks** — Multimodal (DeepMind), Alignment (Anthropic), Reasoning (OpenAI)
- 🌙 **Dark/Light mode** toggle
- 🔍 **Sidebar search** to find any week or topic instantly

## 📸 Preview

| Dark Mode | Light Mode |
|-----------|------------|
| ![Dark](https://img.shields.io/badge/Theme-Dark-1a1a2e?style=for-the-badge&labelColor=07070c) | ![Light](https://img.shields.io/badge/Theme-Light-f5f5f8?style=for-the-badge&labelColor=eaeaf0) |

> **[🔗 Live Demo →](https://ai-pratik.github.io/llm-roadmap/)** *(Enable GitHub Pages to activate)*

---

## 🗺️ Curriculum Overview

| Month | Focus | Key Topics |
|-------|-------|------------|
| **W0** | Prerequisites | Linear Algebra, Calculus, Probability, PyTorch basics |
| **M1** | Transformer Foundations | Attention, BERT, Scaling Laws, MoE, SSMs, GQA, RAG, GraphRAG, Embeddings |
| **M2** | Advanced RAG + Fine-Tuning | Reranking, HyDE, Production RAG, LoRA/QLoRA, DPO/SimPO |
| **M3** | Scale + Serving | Data curation, vLLM, RAFT, Capstone #2 |
| **M3.5** | Advanced AI/ML ★NEW | Knowledge Distillation, Model Merging, Quantization, Prompt Engineering |
| **M4** | LLM Agents | ReAct, CoT, ToT, Structured Outputs, Multi-Agent, MCP Servers |
| **M5** | MLOps + Security | Evaluations, Red-teaming, Kubernetes, Capstone #1 |
| **M6** | Deep Theory | FlashAttention, Distributed Training, Mechanistic Interpretability, RLHF |
| **M7** | Specialization Tracks | Track A: Multimodal · Track B: Alignment · Track C: Reasoning |
| **M7.5** | Frontier Topics ★NEW | Long-Context Architecture, AI Ethics + Responsible AI |
| **M8–9** | Portfolio + Jobs | Resume, arXiv preprint, mock interviews, applications |

---

## 🎯 What You Can Become

| Role | Salary Range (US) |
|------|-------------------|
| 🔬 **LLM Research Engineer** | $180K–$400K+ |
| ⚡ **ML/AI Engineer** | $150K–$350K |
| 🤖 **AI Agent Developer** | $140K–$300K |
| 🛡️ **AI Safety Researcher** | $170K–$380K |
| 📊 **Applied AI Scientist** | $160K–$350K |
| 👁️ **Multimodal AI Engineer** | $155K–$340K |

---

## 🛠️ Features

### Interactive Learning
- **Progress Tracking** — Check tasks as you complete them. Progress saves to `localStorage` automatically
- **Export/Import** — Share your progress via URL. Open the exported URL on any device to restore
- **Completion Calculator** — Enter your study hours/week to see estimated finish date

### Visual Design
- **Animated Hero** — Rotating gradient background with floating orbs
- **Glassmorphism Cards** — Company target cards for Anthropic, OpenAI, DeepMind
- **Timeline Visualization** — Interactive 10-month learning journey
- **Scroll Animations** — Sections fade in as you scroll
- **Stats Counter** — Animated count-up on page load

### AI/ML Content
- **Industry Landscape** — 6 hot research areas in 2025
- **Key Concepts Grid** — 8 foundational AI/ML concepts you'll master
- **Research Breakthroughs** — Timeline from "Attention Is All You Need" (2017) to present
- **Career Paths** — 6 roles with skills and salary ranges

---

## 📂 Repository Structure

```
llm-roadmap/
├── index.html              # Main roadmap (single-page app)
├── README.md               # This file
├── papers/                 # 12 print-worthy research papers (PDFs)
│   ├── Attention-is-all-you-need.pdf
│   ├── BERT.pdf
│   ├── Chain-of-Thought.pdf
│   ├── Constitutional AI.pdf
│   ├── DPO.pdf
│   ├── FlashAttention-2.pdf
│   ├── LoRA.pdf
│   ├── QLoRA.pdf
│   ├── ReAct.pdf
│   ├── Scaling Laws.pdf
│   └── InstructGPT.pdf
└── printable/              # Printable reference sheets
    ├── llm_printable_reference.html
    └── llm_printable_reference_part2.html
```

---

## 🚀 Getting Started

### Option 1: GitHub Pages (Recommended)
1. Fork this repository
2. Go to **Settings → Pages → Source: main branch**
3. Your roadmap is live at `https://yourusername.github.io/llm-roadmap/`

### Option 2: Local
```bash
git clone https://github.com/ai-pratik/llm-roadmap.git
cd llm-roadmap
open index.html    # macOS
# or
xdg-open index.html  # Linux
```

### Option 3: VS Code Live Server
1. Clone the repo
2. Open in VS Code
3. Install "Live Server" extension
4. Right-click `index.html` → "Open with Live Server"

---

## 🔄 Regular Updates

This roadmap is **actively maintained** and updated regularly with:

- 📄 New papers as they're published (arXiv, top conferences)
- 🛠️ New tools and frameworks as the ecosystem evolves
- 🏢 Updated company focus areas based on hiring trends
- 💰 Salary ranges reflecting current market data
- 🧪 New build tasks aligned with industry best practices
- 🗓️ Timeline adjustments based on community feedback

### Update Schedule
| Frequency | What Gets Updated |
|-----------|-------------------|
| **Weekly** | New papers, tools, and resources as they drop |
| **Monthly** | Build tasks, salary data, company focus areas |
| **Quarterly** | Major curriculum restructuring, new weeks/tracks |

### How to Stay Updated
⭐ **Star this repo** to get notified of updates in your GitHub feed.

```bash
# Pull latest changes
git pull origin main
```

> **Note:** Your progress is stored in your browser's `localStorage`, so pulling updates won't reset your progress.

---

## 📋 Changelog

### v3.1 — March 2026 (Current)
- ✨ Animated hero with gradient + floating orbs + typing tagline
- 🌙 Dark/light mode toggle
- 🔍 Sidebar search functionality
- 🎯 Glassmorphism company target cards
- 🚀 6 AI/ML career paths with salary ranges
- 🌐 Industry landscape — 6 hot research areas
- 🧬 8 key AI/ML concepts grid
- 📅 Research breakthroughs timeline (2017–2025)
- ⏱️ Completion date calculator
- 🤝 Community footer
- **NEW W4.5** — GraphRAG + Knowledge Graphs
- **NEW W4.7** — Embedding Models + Retrieval Training
- **NEW W12.5** — Knowledge Distillation + Model Merging + Quantization
- **NEW W12.7** — Prompt Engineering Mastery
- **NEW W28.5** — Long-Context & Extended Architecture
- **NEW W28.7** — AI Ethics + Responsible AI

### v3.0 — Original
- 38-week curriculum with 55+ papers
- Progress tracking with localStorage
- 3 specialization tracks
- Print-worthy paper collection

---

## 🤝 Contributing

Contributions are welcome! Here's how:

1. **Fork** this repository
2. **Create** a feature branch (`git checkout -b add-new-week`)
3. **Add** your content (new papers, build tasks, resources)
4. **Commit** with a descriptive message
5. **Push** and open a **Pull Request**

### What to Contribute
- 📝 New research papers with annotations
- 🔨 Build tasks with step-by-step instructions
- 🐛 Bug fixes or UI improvements
- 🌍 Translations
- 💡 Suggestions for curriculum improvements

---

## 📜 License

This project is open source under the **[MIT License](LICENSE)**.

**Copyright © 2026 Pratik Gade.** You are free to use, modify, and distribute this roadmap for any purpose — personal, educational, or commercial.

---

## ⭐ Show Your Support

If this roadmap helped you, please:
- ⭐ **Star** this repository
- 🔄 **Share** it with fellow ML engineers
- 📝 **Contribute** improvements back
- 🐦 **Tag** [@pratikgade](https://github.com/ai-pratik) when you share

---

<div align="center">

**Built with ❤️ by [Pratik Gade](https://github.com/ai-pratik) for the AI/ML community** 🧠

*From zero to research lab — one week at a time.*

**Open Source · Free Forever · MIT License**

</div>
