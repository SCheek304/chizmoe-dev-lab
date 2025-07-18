# chizmoe-dev-lab
Coding lab
# 🧪 Chizmoe's Dev Lab

Welcome to your custom development environment — a full-featured dev container designed for Python, Node.js, AI tooling, Bash scripting, and GitHub integration. Perfect for everything from rock-polished web apps to deep AI experiments.

## ⚙️ What's Inside

- **Python 3.11** with AI libraries (transformers, torch, openai)
- **Node.js 18** with Puppeteer, Axios, OpenAI client
- **GitHub CLI** and Copilot support
- **Docker Compose** for managing multi-container projects
- **VS Code Extensions**:
  - Python, Jupyter, Docker, GitHub Copilot
  - Web Inspector, SingleFile, User Scripts
  - ChatGPT integration for real-time code help
- **Auto-open Ports**: 8000, 3000, 5000

## 🚀 How to Use

### 📦 Option 1: GitHub Codespaces
1. Create a new repo and upload the `.devcontainer/` folder.
2. Click `Code > Codespaces > Create codespace on main`.
3. Let it build and dive in!

### 💻 Option 2: VS Code with Dev Containers
1. Install [Remote - Containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers).
2. Open folder in container (`F1 > Reopen in Container`).
3. Start coding!

## 🧠 AI Setup

Install dependencies:

```bash
pip install -r requirements.txt
npm install
```

Optional: add your OpenAI key to VS Code settings for ChatGPT integration:

```json
"chatgpt.tokenKey": "your-api-key-here"
```

## 🔗 GitHub Auth

```bash
gh auth login
```

## 🪄 Project Maintained by

**Chizmoe** aka the Modern-Day Alchemist of Code 🧙‍♂️
