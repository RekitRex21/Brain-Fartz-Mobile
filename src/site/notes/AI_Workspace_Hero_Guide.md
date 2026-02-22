---
{"dg-publish":true,"permalink":"/ai-workspace-hero-guide/"}
---

# 🚀 Mobile AI Workspace: Zero to Hero Guide
**Project:** Brain Fartz Mobile | **Last Updated:** 2026-01-25

This guide documents the exact steps taken to transform a standard Android device into a high-powered, automated AI development environment using Termux, the Gemini CLI, and Obsidian.

---

## 🛠️ Step 1: The Proper Foundation
The Google Play Store version of Termux is outdated. To support modern CLI tools, you must use a current build.

1. **Download:** Get Termux from **F-Droid** or **GitHub**.
2. **Update Repositories:**
   ```bash
   pkg update && pkg upgrade -y
   pkg install python nodejs-lts git -y
   ```

3. **Grant Storage Access:** (Allows the AI to see your Obsidian Vault)
   ```bash
   termux-setup-storage
   ```

## 🧠 Step 2: Configure the AI Engine
The Gemini CLI (v0.26.0) requires a specific configuration to enable "Skills" (Agentic capabilities).

**Command to fix `~/.gemini/settings.json`:**
```bash
python3 -c 'import json, os; p=os.path.expanduser("~/.gemini/settings.json"); d=json.load(open(p)) if os.path.exists(p) else {}; d["experimental"] = {"skills": True}; d["projectRoot"] = "/sdcard/Documents/Brain Fartz Mobile /Brain Fartz Mobile "; json.dump(d, open(p, "w"), indent=2)'
```

## ⚔️ Step 3: Setting Up the Skill Nest
Skills are specialized agents (Writing, Research, Dev) that live inside your vault.

**Create the absolute path directories:**
```bash
mkdir -p "/sdcard/Documents/Brain Fartz Mobile /Brain Fartz Mobile /.gemini/skills/writing"
mkdir -p "/sdcard/Documents/Brain Fartz Mobile /Brain Fartz Mobile /.gemini/skills/research"
mkdir -p "/sdcard/Documents/Brain Fartz Mobile /Brain Fartz Mobile /.gemini/skills/dev-agent"
```
*Note: Ensure the `SKILL.md` files are placed in these folders to activate the agents.*

## ⚡ Step 4: The "Brain" Automation
We created a custom alias to jump into the vault and load all skills with a single word.

**The Alias (Add to `~/.bash_aliases`):**
```bash
alias brain="cd \"/sdcard/Documents/Brain Fartz Mobile /Brain Fartz Mobile \" && gemini -i \"/skills install \\\"/sdcard/Documents/Brain Fartz Mobile /Brain Fartz Mobile /.gemini/skills/writing\\\"; /skills install \\\"/sdcard/Documents/Brain Fartz Mobile /Brain Fartz Mobile /.gemini/skills/research\\\"; /skills install \\\"/sdcard/Documents/Brain Fartz Mobile /Brain Fartz Mobile /.gemini/skills/dev-agent\\\"\""
```
After adding, run `source ~/.bashrc` to activate.

## 🎮 Step 5: Master Commands
| Goal | Command |
|---|---|
| Start Session | `brain` |
| List Skills | `/skills list` |
| Refresh Memory | `/memory refresh` |
| Create Note | `"Use writing-pro to create [filename].md"` |
| Exit Session | `/exit` |

---
*Created via Brain Fartz Mobile Automation.*

### **Final Pro-Tip:**
Once you've created this file, it will appear in your Obsidian sidebar. Since it’s an `.md` file, all those code blocks will have "Copy" buttons in Obsidian, making it easy to replicate the setup later!