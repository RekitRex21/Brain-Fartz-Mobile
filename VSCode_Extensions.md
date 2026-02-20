# VS Code Extensions for AI Workflow

## Quick Install
```bash
code --install-extension <extension-id>
```

## 1. AI & Ollama Integration

| Extension | ID | Purpose |
|-----------|-----|---------|
| Continue | continue.continue | Connect to local Ollama models |
| Roo Code | roovygity.roo-code | Agentic coding (Claude/Cline alternative) |
| Ollama | jmikhail.ollama | Ollama Modelfile syntax highlighting |

## 2. Markdown & Obsidian

| Extension | ID | Purpose |
|-----------|-----|---------|
| Markdown All in One | yzhang.markdown-all-in-one | TOC, shortcuts, tables |
| Markdown Preview Enhanced | shd101wyy.markdown-preview-enhanced | Math, Mermaid diagrams |
| Markdownlint | DavidAnson.vscode-markdownlint | Lint and fix issues |
| Obsidian | zc.design-obsidian-viewer | View Obsidian vault in VS Code |

## 3. Python & Go

| Extension | ID | Purpose |
|-----------|-----|---------|
| Python | ms-python.python | Official Python support |
| Pylance | ms-python.vscode-pylance | Fast IntelliSense |
| Go | golang.go | Official Go extension |
| Ruff | charliermarsh.ruff | Fast linter + formatter |

## 4. Productivity & Config

| Extension | ID | Purpose |
|-----------|-----|---------|
| Error Lens | usernamehw.errorlens | Inline error highlighting |
| YAML | redhat.vscode-yaml | YAML validation |
| GitLens | eamodio.gitlens | Git blame, history |

## Install All at Once

Copy this into terminal:
```bash
# AI
code --install-extension continue.continue
code --install-extension roovygity.roo-code
code --install-extension jmikhail.ollama

# Markdown
code --install-extension yzhang.markdown-all-in-one
code --install-extension shd101wyy.markdown-preview-enhanced
code --install-extension DavidAnson.vscode-markdownlint
code --install-extension zc.design-obsidian-viewer

# Coding
code --install-extension ms-python.python
code --install-extension ms-python.vscode-pylance
code --install-extension golang.go
code --install-extension charliermarsh.ruff

# Productivity
code --install-extension usernamehw.errorlens
code --install-extension redhat.vscode-yaml
code --install-extension eamodio.gitlens
```

## Usage Notes

- **Continue**: Connects to local Ollama - keep Ollama running
- **Modelfiles**: Use YAML or Shell filetype for syntax highlighting
- **Python**: F5 to run scripts directly in terminal
- **GitLens**: View who changed what, when
