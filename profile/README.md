# CrepBook

**CrepBook** is an AI-first notes app for **desktop + mobile** that turns a single large document into a clean, navigable knowledge base — without losing the simplicity of writing in Markdown.

The core idea is simple: you can **write everything in one place**, and BlockNote will help you **split, structure, tag, link, and search** it like a real knowledge system. AI is not a plugin here — it’s deeply embedded into the workflow as both a **knowledge assistant** and a **writing companion**.

---

## 🙋‍♀️ What we’re building

BlockNote focuses on three pillars:

- **One big file → many small notes**  
  Work in a single “stream” (journal / draft / raw dump) and let BlockNote split it into smaller, reusable notes for better navigation and reuse.

- **Markdown-first, organization-friendly**  
  Write in Markdown, add **tags**, keep structure predictable, and maintain readable storage.

- **Deep AI integration (local + remote models)**  
  Use AI to summarize, rewrite, extract key points, build outlines, answer questions from your notes, and help you write — with support for both **local models** and **remote providers**.

---

## ✨ Key features (WIP)

- **Markdown editor** with fast navigation
- **Automatic note splitting** from a large document (sections → notes)
- **Tags** and lightweight organization
- **Offline-first** workflow
- **Sync** between desktop and mobile
- AI tools:
  - contextual Q&A over your notes
  - summaries and highlights
  - writing assistance (drafting, rewriting, tone, structure)
  - knowledge extraction (turn raw text into structured notes)

---

## 🧱 Tech stack

Client apps:

- **Tauri** (desktop)
- **Rust + JS/TS** (app core + UI)

Sync:

- Custom **sync server in C++**

AI:

- Support for **local models** (privacy/offline where possible)
- Support for **remote models** (quality / speed / advanced reasoning)

---

## 🌈 Contributing

Contributions are welcome — especially early feedback and bug reports.

Ways to help:

- **Open an issue** (bugs, UX notes, feature requests)
- **Propose improvements** to note-splitting, tagging, navigation, sync UX
- **Submit a PR** (small focused changes are easiest to review)

Guidelines:

- Keep PRs small and well-scoped
- Describe *why* the change is needed (not only what changed)
- Add tests when it makes sense (or describe how you manually tested)

> See: `CONTRIBUTING.md` (add this file when ready)

---

## 👩‍💻 Resources

- 📌 Roadmap: `ROADMAP.md` (placeholder)
- 📚 Docs: `docs/` (placeholder)
- 🧩 Architecture notes: `docs/architecture.md` (placeholder)
- 🐛 Issues: GitHub Issues tab

If you’re using CrepBook and something feels off — UX, sync, AI behavior — open an issue. Early feedback shapes the product.

---

## 🍿 Fun facts

- The project is built around a real pain: **notes grow into one giant file**, and navigation becomes the bottleneck — BlockNote fights that directly.
- Fueled by **coffee**, Markdown, and the dream of a calm, offline-first knowledge workflow.

---

## 🧙 Markdown power

This org uses Markdown everywhere: docs, specs, architecture notes — everything should stay readable in plain text.
