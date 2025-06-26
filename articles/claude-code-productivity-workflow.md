# Productivity Workflow Using Claude Code

This document outlines an effective workflow for using **Claude Code** productively, based on real-world usage strategies. These steps will help you collaborate better with the tool, minimize errors, and maintain control over your codebase during AI-assisted development.

---

## 🧠 Step 1: Start with Plan Mode
- Press `Shift + Tab` to enable **Plan Mode**.
- Claude will **think through** the problem but **not modify any code**.
- Use this to:
  - Review its proposed steps (the "game plan").
  - Approve or revise the plan before execution.

> 💡 *Always begin in Plan Mode to stay in control of changes.*

---

## 📘 Step 2: Use `claude.md` as Memory
- This file stores Claude’s working memory and rules.
- Run `/init` in any codebase to auto-generate the `claude.md`.
- You can modify this file or ask Claude to update it with new reminders.

> 🎯 *Think of `claude.md` like a rulebook Claude follows while working.*

---

## 🧾 Step 3: Commit Frequently (Git = Checkpoints)
- Claude Code lacks a restore feature.
- Use Git commits as **manual checkpoints**:
  - Commit when satisfied.
  - Revert or discard when needed.

> 🛡️ *Use Git to undo unwanted changes made by Claude.*

---

## 🖼️ Step 4: Drag in Screenshots
- Drag screenshots into Claude’s chat for better context.
- Especially helpful for:
  - Error messages.
  - UI design elements.

> 📎 *Visual input gives Claude more accurate context.*

---

## 📁 Step 5: Drag in Other Codebase Folders
- Drag in folders from related projects (e.g., backend while working on frontend).
- Claude can use the context and even modify files **if given permission**.

> 🚀 *Useful workaround for multi-repo workflows.*

---

## 🌐 Step 6: Provide URLs & Docs
- Claude Code can browse the web!
- You can:
  - Paste documentation URLs.
  - Ask it to perform web searches.

> 🔍 *“Use the latest Google Calendar API” — Claude will find it on its own.*

---

## 🧩 Step 7: Use Sub-Agents for Large Tasks
- Claude can create **sub-agents** (parallel workers).
- Great for large-scale tasks (e.g., porting apps).
- Saves time by running processes in parallel.

> ⚙️ *Think of sub-agents as Claude’s multithreading capability.*

---

## ✔️ Step 8: Ask It to Double-Check Its Work
- After code generation:
  - Ask Claude to test for edge cases.
  - Have it review potential breakages.

> 🔍 *Extra sanity check — it often catches things you might miss.*

---

## 🔍 Step 9: Review All Output Manually
- Treat Claude’s code as if it were written by another dev.
- Always review before merging.

> ✅ *Claude is powerful, but blind trust is risky.*

---

## Final Thoughts
Claude Code is an excellent productivity companion, but works best when used deliberately. Following this workflow ensures:
- Better results.
- Greater control.
- Fewer surprises in your codebase.