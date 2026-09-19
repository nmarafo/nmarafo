# 👋 Hi, I’m Norberto Martín Afonso

> **EdTech Software Architect & Full-Stack Developer**  
> Architecting secure enterprise cloud systems, privacy-first local AI agents with WebGPU, Open Knowledge Frameworks (OKF), and interactive educational game experiences.

[![GitHub Followers](https://img.shields.io/github/followers/nmarafo?style=social)](https://github.com/nmarafo)
[![Twitter Follow](https://img.shields.io/twitter/follow/NorbertoMartnAf?style=social)](https://twitter.com/NorbertoMartnAf)

---

## 🛠️ Core Tech Stack

```text
Languages:     PHP (8.2+) • Python (3.9+) • Dart • JavaScript / TypeScript
Cloud & Sec:   Nextcloud Core & Apps • Collabora Online (CODE) / WOPI • Docker • ENS (RD 311/2022) • SSE (AES-256)
Local AI & ML: WebGPU • @huggingface/transformers • ONNX Runtime • Gemma 4 • OKF (Open Knowledge Framework)
Game & EdTech: Flutter • Flame Engine • Rive • Moodle LMS • Google Workspace IaC • H5P
```

---

## 🚀 Featured Projects

### 🛡️ Enterprise Cloud & Nextcloud Security

* **[Nextcloud Secure Office](https://github.com/nmarafo/nextcloud-secure-office)**  
  [![Nextcloud](https://img.shields.io/badge/Nextcloud-33%2B-0082c9.svg)](https://nextcloud.com/)
  [![Compliance](https://img.shields.io/badge/Compliance-ENS%20(RD%20311%2F2022)%20Alto-green.svg)](https://www.ccn-cert.cni.es/ens.html)
  [![License: AGPL v3](https://img.shields.io/badge/License-AGPL_v3-blue.svg)](https://github.com/nmarafo/nextcloud-secure-office/blob/main/LICENSE)  
  Enterprise-grade security extension for **Nextcloud 33+** engineered to enforce the Spanish National Security Framework (**Esquema Nacional de Seguridad - ENS RD 311/2022, Nivel Alto**):
  * **WOPI Security Middleware**: Intercepts `checkFileInfo` calls between Nextcloud and Collabora Online (CODE) to dynamically inject non-removable forensic watermarks (`WatermarkText`) with authenticated user identity, IP address, and classification labels.
  * **Data Loss Prevention (DLP)**: Enforces export, copy, and print prohibitions (`DisableExport`, `DisableCopy`, `DisablePrint`) within collaborative office sessions.
  * **At-Rest Encryption**: Integrates with Nextcloud Server-Side Encryption (Master Key AES-256-CTR) ensuring raw files remain encrypted on disk.
  * **Immutable Audit Trail & CLI**: Persistent activity logging with CSV export and real-time compliance diagnostics (`php occ secure_office:ens-audit`).

---

### 🧠 Autonomous AI Agents, WebGPU & Open Knowledge Framework (OKF)

* **[OpenDidactia](https://github.com/nmarafo/OpenDidactia)**  
  [![Framework: OKF](https://img.shields.io/badge/Framework-OKF_v1.3-blue.svg)](https://github.com/nmarafo/OpenDidactia)
  [![Coverage](https://img.shields.io/badge/Cobertura-17_CCAA_+_Ceuta_y_Melilla-green.svg)](https://github.com/nmarafo/OpenDidactia)  
  Structured Open Knowledge Framework (OKF) and modular curricular schemas designed for automated, AI-assisted generation of **Didactic Planning (*Programaciones Didácticas*)** and **Learning Situations (*Situaciones de Aprendizaje*)** under LOMLOE across all **17 Autonomous Communities and 2 Autonomous Cities**. Built with native support for Universal Design for Learning (UDL / DUA), David Merrill's First Principles of Instruction, active methodologies (PBL, Service Learning, Design Thinking), and Harvard Project Zero visible thinking routines.

* **[open-lex-edu](https://github.com/nmarafo/open-lex-edu)**  
  [![Standard: OKF](https://img.shields.io/badge/Standard-OKF%20Legislation-purple.svg)](https://github.com/nmarafo/open-lex-edu)  
  Standardized open repository transcribing and structuring Spanish national and regional educational legislation into YAML frontmatter and Markdown schemas, optimized for direct ingestion by autonomous LLM agents and legal RAG pipelines.

* **[local-gemma4-rag](https://github.com/nmarafo/local-gemma4-rag)**  
  [![WebGPU Local AI](https://img.shields.io/badge/Inference-WebGPU%20Local%20AI-orange.svg)](https://github.com/nmarafo/local-gemma4-rag)  
  Privacy-first, 100% in-browser multimodal document assistant and RAG pipeline running entirely inside the client's web browser using `@huggingface/transformers`, **WebGPU**, and **Gemma 4 ONNX** models. Zero cloud dependencies, zero external API keys, and complete data confidentiality.

* **[exelearning-ai-compiler](https://github.com/nmarafo/exelearning-ai-compiler)**  
  [![eXeLearning](https://img.shields.io/badge/eXeLearning-v4.0.0-blue.svg)](https://github.com/nmarafo/exelearning-ai-compiler)  
  WebGPU-powered compiler application running client-side Gemma 4 ONNX models to automatically craft pedagogical learning sequences and compile production-ready `.elpx` and `content.xml` packages for **eXeLearning v4.0.0**.

---

### 🎮 Educational Game Development & Gamification

* **[open-game-edu](https://github.com/nmarafo/open-game-edu)**  
  [![Engine: Apps Script V8](https://img.shields.io/badge/Google%20Apps%20Script-V8%20Engine-4285F4.svg?logo=google)](https://github.com/nmarafo/open-game-edu)
  [![Multiplayer](https://img.shields.io/badge/Multiplayer-Sub--80ms%20CacheService-ff69b4.svg)](https://github.com/nmarafo/open-game-edu)  
  Open Knowledge Framework (OKF) and Infrastructure as Code (IaC) platform for educational gaming in Google Workspace. Features 5 game modes, synchronized live multiplayer powered by `CacheService` (sub-80ms), automated competency telemetry in Google Sheets, and curricular alignment with official evaluation criteria.

* **[Tamogante](https://apps.apple.com/es/app/tamogante/id1537266465)**  
  Educational video game for cultural heritage learning:
  * 🍏 [App Store (iOS)](https://apps.apple.com/es/app/tamogante/id1537266465)
  * 🌐 [Web Demo](https://nmarafo.github.io/tamogante/)

* **Interactive Web Demos & Flame Engine Games**:
  * [🎮 Tamogante Web Demo](https://nmarafo.github.io/tamogante/) — Educational adventure web version.
  * [👁️ Eyes Mouse](https://nmarafo.github.io/eyes_mouse/) — Interactive gaze and cursor tracking experience.
  * [🚀 Planet Scape](https://nmarafo.github.io/planet_scape/) — 2D space arcade built with Flame Engine.
  * [🕹️ Minijuegos Play](https://github.com/nmarafo/minijuegosplayv2) — Suite of web-based educational mini-games.
  * [✨ Flame Character Animator](https://github.com/nmarafo/flame-character-animator) — Character animation controller and physics tool.

---

### 🔌 LMS & Educational Platform Integrations

* **[Moodle Atto Ace Inline Assistant](https://github.com/nmarafo/moodle-atto_aceinlineassistant)**  
  Official plugin available on the [Moodle Plugins Directory](https://moodle.org/plugins/atto_aceinlineassistant), embedding the Ace code editor directly into Moodle's Atto rich-text editor for seamless syntax highlighting and live code editing.

* **Interactive Educational Web Tools (Flutter & H5P)**:
  * [📱 Canary QR](https://nmarafo.github.io/canary_qr/) — Educational QR generator and scanner.
  * [🎡 Definitions Spinner](https://nmarafo.github.io/definition_spinner/) — Interactive classroom vocabulary spinner.
  * [📹 Videoconferencias en EVAGD](https://nmarafo.github.io/videoconferencias_evagd/) — Video conference integration guide for virtual learning environments.
  * [📚 Guía de Recursos Multimedia](https://nmarafo.github.io/recursos_canarias_curso/) — Free multimedia resources guide for educators.
  * [📑 Clasificador Currículo](https://nmarafo.github.io/clasificador_curriculo_lomce) — Interactive curriculum classifier.

---

## 📫 Connect with Me

* 💼 **GitHub**: [@nmarafo](https://github.com/nmarafo)
* 🐦 **Twitter / X**: [@NorbertoMartnAf](https://twitter.com/NorbertoMartnAf)
* 📧 **Email**: [normaafo@gmail.com](mailto:normaafo@gmail.com)
