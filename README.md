# Hi, I'm Esteban Padilla 👋

Junior developer working on applied AI for document processing — OCR and NLP pipelines that run **entirely on local inference**, no external AI calls in the main flow.

> "Any fool can write code that a computer can understand.
> Good programmers write code that humans can understand."
>
> — Martin Fowler, *Refactoring*

---

## Featured Project

### [Email-Automation](https://github.com/estebanp26/Email-Automation) · `Python`

Automated ingestion, evaluation, and response of absence justifications for an HSE team.

An email arrives with a PDF attached. The system reads it, decides whether the justification is valid, and either replies automatically or flags it for a human to review.

| Piece | Tech |
|---|---|
| **Strata Core** — document engine | FastAPI, PyMuPDF, Tesseract OCR, Qwen 2.5 via Ollama |
| **Orchestration** | n8n |
| **Persistence** | PostgreSQL 16 + SQL migrations |
| **Dashboard** | React 19, Vite, TypeScript |
| **Mail** | Gmail IMAP listener + Outlook connector |
| **Ops** | Docker, pytest |

**What makes it interesting:**
- **Local-first.** Attachments are processed on-machine. Works with Ollama offline and degrades to a deterministic fallback if the model isn't up.
- **Separation of concerns enforced.** n8n does no OCR and no inference — it consumes the engine over HTTP. The engine handles no identity management.
- **Guardrails before AI.** Deterministic rules and a confidence threshold decide what reaches the model; low-confidence cases go to manual review instead of guessing.
- **Tested.** 9 pytest suites covering RBAC, security, performance indexes, and workflow simulation.

---

## Tech Stack

**Languages**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=Python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=TypeScript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=JavaScript&logoColor=black)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat&logo=GNU-Bash&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-025E8C?style=flat)

**AI & Document Processing**
![Ollama](https://img.shields.io/badge/Ollama-FFFFFF?style=flat&logo=Ollama&logoColor=black)
![Qwen](https://img.shields.io/badge/Qwen_2.5-FFFFFF?style=flat)
![Tesseract](https://img.shields.io/badge/Tesseract_OCR_5-FFFFFF?style=flat)
![PyMuPDF](https://img.shields.io/badge/PyMuPDF-FFFFFF?style=flat)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=NumPy&logoColor=white)
![Pillow](https://img.shields.io/badge/Pillow-FFFFFF?style=flat)

**Backend & Data**
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=FastAPI&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=Node.js&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=PostgreSQL&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=MongoDB&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat&logo=SQLite&logoColor=white)

**Frontend**
![React](https://img.shields.io/badge/React_19-61DAFB?style=flat&logo=React&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat&logo=Vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat&logo=Tailwind-CSS&logoColor=white)

**Environment & Automation**
![Arch Linux](https://img.shields.io/badge/Arch_Linux-1793D1?style=flat&logo=Arch&logoColor=white)
![Hyprland](https://img.shields.io/badge/Hyprland-00A3E0?style=flat)
![Wayland](https://img.shields.io/badge/Wayland-1A1A1A?style=flat)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=Docker&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat&logo=n8n&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=Git&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat&logo=Visual-Studio-Code&logoColor=white)

---

## Currently Learning

**Data analytics** — turning the pipelines I build into dashboards people actually read.

## Beyond Code

🎮 Video games, without exception.
🦸 Marvel Cinematic Universe, without limits.

---

*`"Hacking"`*
<!--
**estebanp26/estebanp26** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
