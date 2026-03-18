<p align="center">
  <h1 align="center">🤡 List Clown</h1>
</p>

<p align="center">
  <strong>The Ultimate AI Pair Programmer for your Terminal</strong>
  <br>
  <em>Powered by List AI & OpenRouter</em>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/List%20AI-Powered-red?style=for-the-badge" alt="List AI Powered">
  <img src="https://img.shields.io/badge/Model-List--Kimi--10M-yellow?style=for-the-badge" alt="Model List-Kimi-10M">
  <img src="https://img.shields.io/badge/License-Apache%202.0-blue?style=for-the-badge" alt="License">
</p>

---

## 🚀 What is List Clown?

**List Clown** is a powerful, terminal-based AI pair programmer based on the robust Open Clown / Aider architecture, enhanced and customized by **List AI**. It allows you to edit code in your local git repository with the help of advanced Large Language Models (LLMs).

We've supercharged the experience with:
- **Custom List AI Branding**: A beautiful, modern CLI interface.
- **Optimized Defaults**: Auto-linting, auto-commits, and chat history enabled out of the box.
- **Powerful Models**: Pre-configured to use the high-performance `list-ai/list-kimi-10M` (via OpenRouter).

## ✨ Key Features

- **🧠 Smart Context**: List Clown maps your entire codebase to understand the context of your project.
- **🎨 Beautiful UI**: A custom-designed, colorful terminal interface with a unique banner.
- **⚡ Auto-Correction**: Automatically runs linters and fixes errors before you even see them.
- **💾 Persistent Chat**: Never lose your context – chat history is restored automatically.
- **🌐 Web Capable**: Can search the web for real-time information to solve your coding problems.
- **🛡️ Git Integrated**: Changes are automatically committed with descriptive messages.

## 🛠️ Installation

To get started with List Clown, simply install the package:

```bash
pip install -e .
```

## 🎮 Usage

Run `List-Clown` in your terminal within a git repository:

```bash
List-Clown
```

### Common Commands

- `/add <file>`: Add a file to the chat context.
- `/drop <file>`: Remove a file from the chat context.
- `/undo`: Undo the last change.
- `/diff`: Show the changes made.
- `/web <query>`: Search the web for information.
- `/help`: Show all available commands.

## ⚙️ Configuration

List Clown comes pre-configured for the best experience.
- **Model**: `list-ai/list-kimi-10M` (OpenRouter/list-ai/list-kimi-10M)
- **Edit Format**: Whole file editing (most reliable)
- **Theme**: Dark mode optimized

## 🤝 Credits

Based on the amazing [Aider](https://github.com/paul-gauthier/aider) project.
Customized and enhanced by **List AI**.

---

