# 🤖 AI Usage Guide – HT Copilot Workspaces

Welcome to your AI-augmented development system.  
This guide explains **how to use GitHub Copilot Chat across your 3 primary repos** using repo-specific `space.json` files.

---

## 🗂️ Repo Overview & Roles

| Repo Name           | Role                                     | Copilot Purpose |
|---------------------|------------------------------------------|------------------|
| `HT-Toolbox`        | BIM Automation Scripts (pyRevit, Revit API) | Understand, test, and extend custom Revit tools |
| `HT-AI-Playground`  | Prompt Vault & AI Assistant Dev           | Prompt engineering, ideation, multi-tool experiments |
| `HT-Portfolio`      | Web Portfolio & Branding Site             | Content, design, SEO, and personal branding help |

---

## 🧠 General Copilot Workflow (VS Code)

1. Clone the repo locally
2. Open it in **VS Code**
3. Ensure you’ve installed:
   - `GitHub Copilot` (extension)
   - `GitHub Copilot Chat` (for assistant panel)
4. In the sidebar, open **Copilot Chat** tab
5. Ask questions based on that repo’s `space.json` and context

---

## 🧰 HT-Toolbox – Developer Assistant

> 💡 Use this space to explore, debug, refactor, or extend your pyRevit + Revit API tools

**Example Prompts:**
- What does `RenameViews.py` do?
- Can you suggest a better UI layout for this pyRevit tool?
- Refactor `FilterByLevel.py` to support Reference Levels too
- Generate unit tests for `PreviewRenameGridForm.py`

**Copilot sees:** `scripts/`, `docs/`, `tests/`  
Make sure tools are properly named and well-commented for AI clarity.

---

## 🧠 HT-AI-Playground – Prompt Engineer Mode

> 💡 Use this space to build prompt workflows, design AI agents, and manage assistant memory

**Example Prompts:**
- Summarize all prompts inside `prompts/`
- Generate 3 new prompts related to Dynamo and UI forms
- Suggest improvements to my personal Revit assistant's tone
- What is the best format to store AI memory logs?

**Copilot sees:**  
- `prompts/` → your markdown prompt library  
- `memory_backups/` → saved AI session content  
- `roadmap/` → future feature plans

---

## 🌐 HT-Portfolio – Branding, Web, Content Assistant

> 💡 Use this repo to write content, improve your portfolio, and generate public-facing material

**Example Prompts:**
- Rewrite `index.html` to include the HT logo and latest Revit tools
- Improve meta tags for SEO on the homepage
- Draft a blog post about `CloneBuddy.py` under Projects
- Convert my README into a visual project card layout

**Copilot sees:** `src/`, `assets/`, `content/`  
Add clear HTML/Markdown comments so Copilot understands your structure better.

---

## 💡 Tips for Effective AI Usage

- 🧭 **Always open one repo at a time in VS Code** to isolate Copilot's context
- 🧠 **Use specific filenames** or folders in your questions (e.g., "FilterByLevel in scripts/")
- 🛠️ Keep `space.json` updated if you add new folders or tools
- 💾 Use markdown files in `prompts/` to grow your assistant’s brain

---

## 🔄 Maintaining AI Context

If you move tools between repos:
- Copy relevant examples to the new `space.json`
- Update `source_paths` so Copilot knows where to look
- Store reusable prompts in Playground’s `prompts/` folder as `.md` files

---

## 🔗 Future Expansion

You can link repos with Git submodules, or even:
- Generate assistant profiles for each space
- Use ChatGPT custom GPTs or NotebookLM to organize your assistant memory further
- Deploy to GitHub Pages from `HT-AI-Playground` for a prompt browser

---

_This system is built by Hani Tartour — AI-native Structural BIM Engineer._  
🧠 Made for the future of BIM tooling and digital craftsmanship.
