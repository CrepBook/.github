# Contributing to CrepBook (BlockNote)

CrepBook is an AI-first notes project:
- **app** — Tauri client (Rust + JS/TS) for desktop & mobile
- **server** — C++ sync server
- **offline-first**, **Markdown-first**, with **tags**, sync, and support for **local + remote AI models**

We appreciate issues, PRs, and feedback. This document explains how to contribute effectively.

---

## 🙋 How to help

You can contribute by:

- Reporting bugs (especially around note splitting, navigation, sync, offline mode)
- Suggesting features / UX improvements
- Improving documentation
- Sending PRs to `app` or `server`

If you’re not sure where to start, open an issue with a short description — we’ll help you scope it.

---

## 🐛 Bug reports

Open an issue and include:

- **Expected vs actual behavior**
- **Steps to reproduce**
- **Environment**
  - Desktop OS (Windows/macOS/Linux) or mobile device + OS version
  - App version / commit SHA
- **Logs** (if available)
- Screenshots / recordings for UI bugs

For sync-related bugs, also include:
- Was it offline/online?
- How many devices were involved?
- Self-hosted server or default setup?

---

## 💡 Feature requests

Please describe:

- The problem you’re solving (why it matters)
- Proposed UX / behavior
- Alternatives considered

The project’s core focus is:
**turning one large Markdown document into smaller linked/tagged notes for fast navigation**.

---

## 🔧 Development notes

This org currently has two main repos:

- `app/` — Tauri (Rust + JS/TS)
- `server/` — C++ sync server

Each repo should document its build/run steps in its own `README.md`.
If you notice missing or outdated steps — PRs to improve docs are very welcome.

---

## ✅ Pull request guidelines

### Scope & style
- Keep PRs **small and focused**
- Avoid unrelated refactors mixed with product changes
- Prefer clear naming over cleverness

### Testing
- If you add a feature/fix, describe how you tested it:
  - manual steps, or
  - unit/integration tests (if present in the repo)

### PR description checklist
Include:
- What changed and **why**
- How to reproduce / verify the change
- Screenshots for UI changes
- Related issue link (if exists)

---

## 🔒 Security

If you discover a security/privacy issue (tokens, sync auth, data leakage), please **do not** open a public issue.  
Instead, contact the maintainer privately (you can open a draft issue asking for a contact method if none is listed yet).

---

## 📜 License

By contributing, you agree that your contributions will be licensed under the same license as the repository you’re contributing to.
