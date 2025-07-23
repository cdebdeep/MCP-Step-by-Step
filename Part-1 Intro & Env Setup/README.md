
# 🛠️ Introduction & Developer Environment Setup Guide

This guide helps you install all the required tools to set up your developer environment for working with Claude, MCP, and AI agents.

---

## 🧰 What You Need to Install

### 🔵 [Visual Studio Code (VS Code)](https://code.visualstudio.com/)
- **Free**
- Use [GitHub Copilot](https://github.com/features/copilot) as your **MCP client** inside VS Code.

![VS Code](https://code.visualstudio.com/assets/images/code-stable.png)

---

### 🐍 [Python](https://www.python.org/)

Make sure to add Python to your environment variables during installation.

![Python](https://www.python.org/static/community_logos/python-logo.png)

---

### 🤖 [Claude Desktop](https://claude.ai/download)

Claude is an AI tool used for natural interaction and running MCP clients.

![Claude](https://cdn.icon-icons.com/icons2/2997/PNG/512/anthropic_claude_logo_icon_187037.png)

---

### ⚡ [UV - Python Package Manager](https://docs.astral.sh/uv/)

Use UV as a fast and efficient dependency manager for Python projects.

![UV](https://avatars.githubusercontent.com/u/143859552?s=200&v=4)

---

### 🟢 [Node.js and NPM](https://nodejs.org/en/download)
#### 🟢 [Differences Between npm and npx](https://www.geeksforgeeks.org/node-js/what-are-the-differences-between-npm-and-npx/)

NPM is used for managing JavaScript dependencies.

![NPM](https://upload.wikimedia.org/wikipedia/commons/d/db/Npm-logo.svg)

---

### 🧠 [OpenAI](https://openai.com/)

Use OpenAI for GPT models and API access.

![OpenAI](https://upload.wikimedia.org/wikipedia/commons/4/4b/OpenAI_Logo.svg)

---

### 🧠 [Gemini](https://ai.google.dev/gemini-api/docs/quickstart/)

Use Google AI for Gemini models and API access.

![Gemini](https://upload.wikimedia.org/wikipedia/commons/thumb/f/f4/Google_Gemini_logo.svg/512px-Google_Gemini_logo.svg.png)

---

### 🐱 [GitHub](https://github.com/)

Version control platform to store and manage your code.

![GitHub](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)

---

### ☁️ [Azure Portal](https://portal.azure.com/#home)

Use Azure Portal for cloud resources, app services, and function apps.

![Azure](https://upload.wikimedia.org/wikipedia/commons/a/a8/Microsoft_Azure_Logo.svg)

---

## 🚀 UV Commands

```bash
uv init
uv venv
uv add mcp[cli]
```

🔗 MCP CLI: [https://github.com/chrishayuk/mcp-cli](https://github.com/chrishayuk/mcp-cli)

---

## 🧪 MCP Commands

```bash
mcp version     # Show the MCP version
mcp dev         # Run a MCP server with the MCP Inspector
mcp run         # Run a MCP server
mcp install     # Install a MCP server in the Claude desktop app
```

---

✅ You’re now ready to build your AI Agent ecosystem!
