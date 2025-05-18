# 🧠 Synapso Devlog

This is the internal development vault for **Synapso** — a local-first, privacy-focused semantic knowledge engine.  
It serves as both a developer diary and a long-term design reference.

> ⚠️ This is **not the source code repo** — it's a working notebook of architecture, decisions, implementation notes, and day-by-day logs.

---

## 🔍 Purpose

- Track all phases of Synapso development
- Log technical decisions and their rationale
- Maintain a living, self-documenting design record
- Share learnings and design philosophy openly

---

## 🧱 Project Structure

| Folder                          | Contents                                               |
|----------------------------------|--------------------------------------------------------|
| `10_Planning/`                 | Vision, goals, MVP timeline, feature backlog          |
| `20_Architecture/`            | System design, schema plans, chunking, LLM strategy    |
| `30_Implementation/`          | Concrete logic, CLI commands, file watchers, BYOM      |
| `40_DevLog/`                  | Daily work logs and engineering notes                  |
| `50_Decisions/`               | Key design tradeoffs and architectural justifications  |
| `60_Testing_and_DX/`          | Testing notes, CLI usage, developer experience         |
| `70_OpenSource_and_Launch/`   | Licensing, versioning, PyPI release steps              |
| `99_Resources/`               | Prior art, community ideas, tools and references       |

---

## 🧪 Usage

This folder is used with [Obsidian](https://obsidian.md) as a knowledge base.  
You can also browse it as plaintext or render it with a static site generator (e.g., Quartz, Obsidian Publish).

---

## 💡 Design Principles

- **Local-first by default** — privacy, speed, simplicity
- **Semantic intelligence** — embed + retrieve + rerank
- **Minimal UX** — CLI first, UI hooks later
- **Bring Your Own Model (BYOM)** — user decides their inference layer

---

## 📅 Timeline

Check [`10_Planning/MVP_Timeline.md`](10_Planning/MVP_Timeline.md) for deliverables and release schedule.  
Active work logs are updated in [`40_DevLog/`](40_DevLog/).

---

## 👤 Maintained by

**Ganesh Palanikumar**  
🔗 [synapso.xyz](https://synapso.xyz) • [github.com/ganesh-palanikumar](https://github.com/ganesh-palanikumar)

---

## 📖 Want to use this template?

Feel free to fork or copy this devlog scaffold for your own OSS projects.  
It’s MIT-licensed and optimized for clarity, structure, and long-term maintainability.