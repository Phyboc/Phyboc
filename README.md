# Hi, I'm Sivasubramani K J 👋

**B.Tech Computer Science @ Amrita Vishwa Vidyapeetham**  
**B.S. Data Science @ IIT Madras**

Building AI systems, developer tools, and software that solve real-world problems.

---

## About Me

I'm a Computer Science undergraduate passionate about building software that combines strong engineering principles with practical AI. My interests lie at the intersection of **Software Engineering**, **Artificial Intelligence**, **Natural Language Processing**, and **Developer Productivity**.

I enjoy designing systems end-to-end—from model pipelines and APIs to user-facing applications—and I believe the best software is maintainable, explainable, and built with clarity.

---

## Currently Working On

- ⚖️ Improving legal-document understanding with section classification and abstractive summarization for Indian Supreme Court judgments
- 🤖 Exploring **Agentic AI** with the Model Context Protocol (MCP)
- 🛠 Building developer tools that improve engineering workflows and accessibility
- 📚 Learning backend engineering, distributed systems, testing, and cloud deployment
- 🎯 Preparing for software engineering internships and AI-focused opportunities

---

## Tech Stack

### Languages

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat&logo=c%2B%2B&logoColor=white)

### AI & Machine Learning

![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat&logo=huggingface&logoColor=black)
![Transformers](https://img.shields.io/badge/Transformers-8B5CF6?style=flat)
![BART](https://img.shields.io/badge/BART-NLP-blueviolet?style=flat)
![Groq](https://img.shields.io/badge/Groq-LLM-black?style=flat)

### Frameworks & Tools

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=node.js&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat&logo=playwright&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=github-actions&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

---

# Featured Projects

## 🤖 [AutoBoard.ai](https://github.com/Phyboc/AutoBoard.ai)

**Enterprise Agentic AI • Amrita × Nitrostack Hackathon**

An MCP server that turns compatible AI assistants into HR and IT orchestration agents for employee onboarding and offboarding.

### Highlights

- Built 10+ MCP tools for Google Workspace, Slack, GitHub, Jira, AWS, training, email, and ticket workflows
- Supports incremental onboarding and offboarding drafts with interactive React widgets
- Includes confirmation guards for destructive operations, audit logging, execution tracking, and health monitoring
- Provides both STDIO and HTTP SSE transports
- Live MCP endpoint: https://autoboardai-6a6483dc-brigadiers-amrita-university-coimbatore.app.nitrocloud.ai

**Tech:** `TypeScript` • `Node.js` • `MCP` • `Nitrostack` • `Zod` • `Next.js` • `React`

---

## ⚖️ [Legal Document Summarizer](https://github.com/Phyboc/Legal-Document-Summarizer)

**Natural Language Processing**

An AI-powered system for turning legal documents into concise, understandable summaries. The project is being extended with section-classifier improvements to better structure and interpret legal text.

The broader research direction combines **TextRank pruning**, **BART fine-tuning**, hierarchical summarization, and citation-aware verification for faithful summaries of Indian Supreme Court judgments.

**Tech:** `Python` • `HuggingFace` • `BART` • `React` • `Vite` • `NLP`

---

## 🛠 [UI-Auditer](https://github.com/Phyboc/UI-Auditer)

**Developer Tool**

A Python CLI that evaluates webpages against five audience personas: Gen-Z, Elderly, Corporate, Minimalist, and Neurodivergent.

UI-Auditer launches a real Chromium browser with Playwright, analyzes computed styles on JavaScript-rendered pages, scores color, typography, density, motion, and interactivity, and produces actionable terminal reports.

### Highlights

- Rule-based audience scoring with persona-specific dealbreakers and A–F grades
- Optional AI-generated CSS fixes through OpenRouter or Groq
- CI-friendly JSON output with `--json`
- Custom CSS output paths with `--output` / `-o`
- Offline-first core functionality with a pip-installable CLI
- Test coverage for persona loading, scoring, dealbreakers, and extraction

**Tech:** `Python 3.11+` • `Playwright` • `Click` • `Rich` • `Requests` • `pytest`

---

## 🎯 [CareerCompass AI](https://github.com/Phyboc/CareerNavigation-Agent)

**Microsoft Agents League Hackathon**

An AI-powered career guidance platform that analyzes learner readiness, identifies skill gaps, and generates personalized learning roadmaps with structured weekly study plans.

**[Live deployment](https://careernavigation-agent.netlify.app/)**

### Highlights

- Streaming, profile-grounded AI mentor chat using Groq SSE
- Multi-agent routing for career mentoring, resume review, and study planning
- Conversational profile intake that asks one question at a time
- Resume analyzer with section-aware parsing, structured project extraction, and fuzzy deduplication
- Fast deterministic analysis with optional background AI enrichment
- Ten career paths, project recommendations, four-phase roadmaps, weekly plans, and exportable Markdown reports
- Local progress history, rate limits, upload caps, timeouts, and deterministic fallbacks when AI is unavailable
- Vitest coverage for the analysis engine, resume extractor, AI provider, intake flow, and rate limiter

**Tech:** `Next.js 16` • `React 19` • `Tailwind CSS 4` • `JavaScript` • `Groq` • `Vitest`

---

## 🧩 [Twiddle Puzzle Solver](https://github.com/Phyboc/Twiddle-Puzzle-Solver)

**Algorithms & Search**

A Java implementation of the Twiddle puzzle with both CLI and Swing interfaces. It compares multiple approaches for solving an N×N board where moves rotate a 2×2 sub-square counter-clockwise.

Includes BFS, A*, bidirectional BFS, iterative-deepening backtracking, top-down DP, MDF DP, and spatial, cycle, and depth-based divide-and-conquer variants. A phase-three report documents the algorithmic work and comparisons.

**Tech:** `Java` • `BFS` • `A*` • `Bidirectional BFS` • `Dynamic Programming` • `Backtracking` • `Java Swing`

---

## 🚗 [Drowsiness Detector](https://github.com/Phyboc/Drowsiness-detector-TechBrigade-)

**Computer Vision & IoT • SmartCityX Hackathon**

A driver-safety prototype using ESP32-CAM, ESP32-DevKit, and an Edge Impulse eye-blink model. If the driver's eyes remain closed for too long, the system triggers a buzzer and sends remote alerts through Blynk Cloud.

Includes Wokwi simulation, a Blynk monitoring dashboard, an Edge Impulse dataset, and circuit documentation.

**Tech:** `ESP32-CAM` • `ESP32` • `Edge Impulse` • `Arduino` • `Wokwi` • `Blynk`

---

# Exploring

- 🤖 Large Language Models and reliable AI applications
- 🧠 Agentic AI, MCP, and tool-using systems
- 🔍 Retrieval-Augmented Generation and document intelligence
- 🌐 Backend engineering and API design
- ☁️ Cloud deployment and CI/CD
- ⚙️ Distributed systems and observability
- 📖 Research-driven software development

---

# Philosophy

> *I enjoy understanding how systems work before building them.*

Whether it's an NLP pipeline, a developer tool, or an AI agent, I prefer designing solutions that are **maintainable**, **explainable**, and **useful** rather than simply adopting the latest technology.

---

# GitHub Stats

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=Phyboc&show_icons=true&theme=dark&hide_border=true&count_private=true)

<br>

![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=Phyboc&theme=dark&hide_border=true)

<br>

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Phyboc&layout=compact&theme=dark&hide_border=true)

</div>

---

# Let's Connect

I'm always happy to connect with fellow developers, researchers, and students interested in software engineering, AI, NLP, and developer tooling.

- 💼 LinkedIn: https://www.linkedin.com/in/sivasubramani-k-j-39424835/
- 📧 Email: sivasubramanikj@gmail.com

---

<div align="center">

⭐ *If you find any of my projects interesting, consider giving them a star!*

Thanks for visiting my profile.

</div>
