# Tool Setup Checklist — FL-01

> **Status key:** ✅ Done · ⏳ Pending (add screenshot to `evidence/` and tick this box)

---

## 1. AI Tool Accounts

| Tool | Account created | Evidence |
|------|----------------|----------|
| **Claude** (claude.ai) | [ ] pending | ![claude-account](../evidence/claude-account.png) |
| **ChatGPT** (chat.openai.com) | [ ] pending | ![chatgpt-account](../evidence/chatgpt-account.png) |
| **Anthropic Academy** (academy.anthropic.com) | [ ] pending | ![academy-enrollment](../evidence/academy-enrollment.png) |

*Replace `[ ] pending` with `[x] done — YYYY-MM-DD` once each account is confirmed and the screenshot is added.*

---

## 2. AI Fluency: Framework & Foundations — Course Enrollment

| Milestone | Status | Evidence |
|-----------|--------|----------|
| Enrolled in "AI Fluency: Framework & Foundations" | [ ] pending | ![academy-enrollment](../evidence/academy-enrollment.png) |
| Module 1 completed | [ ] pending | ![academy-module1-complete](../evidence/academy-module1-complete.png) |

---

## 3. Claude Project Setup

| Step | Status | Evidence |
|------|--------|----------|
| Claude Project created with custom instructions | [ ] pending | ![claude-project-config](../evidence/claude-project-config.png) |

The custom instructions to paste are in [`docs/claude-project-instructions.md`](claude-project-instructions.md).

---

## How to complete this checklist

1. **Take a screenshot** of each item listed in [`evidence/README.md`](../evidence/README.md).
2. **Save the file** with the exact filename specified (e.g., `claude-account.png`).
3. **Place it** in the `evidence/` folder at the repo root.
4. **Update this file** — change `[ ] pending` to `[x] done — YYYY-MM-DD`.
5. **Commit** using: `docs: add tool setup evidence screenshots`

---

> **Note on PDF export:**  
> A PDF export of `docs/workflow-audit.md` was requested. No automated PDF tooling (e.g., `pandoc`) was available in this environment without additional setup. To produce `docs/workflow-audit.pdf`, you can:
> - Open `docs/workflow-audit.md` in VS Code → right-click → "Open Preview" → Print → Save as PDF, or
> - Run `pandoc docs/workflow-audit.md -o docs/workflow-audit.pdf` if you have Pandoc installed.
