# AI Toolchain Research - Rex's Setup

## Executive Summary

Your toolchain = **Local-first with cloud backup**. Privacy meets power.

| Layer | Tool | Use |
|-------|------|-----|
| Assistant | OpenClaw | Me (runs as YOU) |
| Local LLM | Ollama | llama3.2, mistral, qwen2.5 |
| Cloud AI | Gemini CLI | Research (mobile) |
| Notes | Obsidian | Vault synced to GitHub |
| Code | Me + CLI | I do the coding |

---

## How YOU Use Each Tool

### OpenClaw (Your Assistant)
- Runs as a service on your PC (Gateway)
- Connected to Telegram (@cryptobotv2bot)
- Default model: MiniMax-M2.5
- Falls back to MiniMax-M2.5-Lightning
- Skills: Research, coding, automation

**What I do:**
- Execute commands
- Read/write files  
- Manage cron jobs
- Answer questions
- Run trading bots

### Ollama (Local Models)
Your installed models:
```
ollama list
→ llama3.2        (default)
→ mistral         
→ qwen2.5         
→ deepseek-coder-v2
→ qwen2.5-coder:14b
```

**Usage:**
- Code: qwen2.5-coder:14b
- General: llama3.2
- Fast: mistral

### Cloud Tools (When Needed)
| Tool | When | Why |
|------|------|-----|
| Gemini CLI | Mobile research | Fast, good vision |
| Perplexity | Deep research | Citations |
| ChatGPT | Complex coding | Best reasoning |

---

## Recommended Workflow

```
┌──────────────────────────────────────┐
│  NEED: Quick question or task        │
└──────────────┬───────────────────────┘
               ↓
        ┌──────┴──────┐
        │  LOCAL?     │
        └──────┬──────┘
               ↓
        ┌──────┴──────┐
        │   YES       │ NO
        ↓             ↓
┌───────────────┐  ┌───────────────┐
│ Me + Ollama  │  │ Gemini CLI   │
│ (Private,    │  │ (Cloud,      │
│  Fast)       │  │  Mobile)     │
└───────────────┘  └───────────────┘
```

---

## Strengths
- ✅ Privacy - data stays local
- ✅ Speed - no API latency
- ✅ Control - you own the stack
- ✅ Mobile - Termux + cloud

## Gaps
- No unified routing
- No automated logging
- Mobile AI limited (Termux)

---

## Recommendations

1. **Create Modelfiles** for Stranded Compute
2. **Add session logging** to Obsidian  
3. **Keep current setup** - it's solid
