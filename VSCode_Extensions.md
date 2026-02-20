# VS Code Extensions for AI Workflow

## Install All at Once
Copy and paste this into your terminal:

```
# AI & Ollama
code --install-extension continue.continue
code --install-extension jmikhail.ollama

# OpenClaw & Node.js
code --install-extension ms-vscode.powershell
code --install-extension dbaeumer.vscode-eslint

# Markdown & Obsidian
code --install-extension yzhang.markdown-all-in-one
code --install-extension DavidAnson.vscode-markdownlint

# Productivity
code --install-extension eamodio.gitlens
code --install-extension redhat.vscode-yaml
```

## Quick Install
```
code --install-extension <extension-id>
```

## 1. AI & Ollama

| Extension | ID | Purpose |
|-----------|-----|---------|
| Continue | continue.continue | Connect to local Ollama models |
| Ollama | jmikhail.ollama | Ollama Modelfile syntax highlighting |

## 2. OpenClaw & Node.js

| Extension | ID | Purpose |
|-----------|-----|---------|
| PowerShell | ms-vscode.powershell | For OpenClaw CLI commands |
| ESLint | dbaeumer.vscode-eslint | JavaScript/TypeScript linting |

## 3. Markdown & Obsidian

| Extension | ID | Purpose |
|-----------|-----|---------|
| Markdown All in One | yzhang.markdown-all-in-one | TOC, shortcuts, tables |
| Markdownlint | DavidAnson.vscode-markdownlint | Lint and fix issues |

## 4. Productivity & Config

| Extension | ID | Purpose |
|-----------|-----|---------|
| GitLens | eamodio.gitlens | Git blame, history |
| YAML | redhat.vscode-yaml | YAML validation |

## Our Current Models (Base)

- **Ollama**: llama3.2, qwen2.5, mistral
- **OpenClaw**: MiniMax-M2.5 (default)

## Notes

- **Modelfiles**: Use YAML filetype for syntax highlighting
- **Ollama**: Keep Ollama running in background
- **Continue**: Connect to http://localhost:11434
