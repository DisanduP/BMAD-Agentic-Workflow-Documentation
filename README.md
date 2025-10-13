# BMAD Agentic Framework Documentation

## Overview

The BMAD Agentic Framework enables seamless orchestration of agent workflows through a CLI and orchestrator interface. Follow the instructions below to install, verify, and interact with the BMAD system.

---

## 🚀 Getting Started

### 1. Switch to the `v6-alpha` Branch

```bash
git fetch --all && git checkout v6-alpha || git checkout -b v6-alpha origin/v6-alpha
```

✅ You should now be on the `v6-alpha` branch.

---

### 2. Install Dependencies

```bash
if [ -f package-lock.json ]; then npm ci; else npm install; fi
```

This ensures all BMAD CLI dependencies like `commander` are installed correctly.

---

### 3. Install BMAD Dependencies

```bash
npx bmad-method install
```

This command sets up the BMAD Agentic Framework environment.

---

### 4. Verify Installation

```bash
npx bmad-method --version
```

Displays the version of the BMAD Agentic Framework currently installed.

---

## 🎛 Starting the Orchestrator in VS Code Chat

1. Open the **Workspace Chat Pane** in VS Code.
2. Type the following command to start the orchestrator:

```
*agents bmad-orchestrator
```

*You can also use:*

```
*agents bmad/master
*agents bmad/orchestrator
```

---

## 📌 Available Commands (Web Orchestrator Menu)

| Command                | Description                                                                                                  |
| ---------------------- | ------------------------------------------------------------------------------------------------------------ |
| `*list-agents`         | List all available agents                                                                                    |
| `*agents [agent-name]` | Switch to a specific agent — e.g. `*agents bmm/analyst`, `*agents bmm/architect`, `*agents bmb/bmad-builder` |
| `*party-mode`          | Enter multi-agent group chat mode                                                                            |
| `*help`                | Display help menu and available commands                                                                     |
| `*exit`                | Exit the orchestrator session                                                                                |

---

## ✅ Example Agent Switch Commands

```bash
*agents bmm/analyst
*agents bmm/architect
*agents bmb/bmad-builder
```

---

## 🎉 You're Ready!

Your BMAD Agentic Framework setup is now complete. You can now orchestrate intelligent workflows using the BMAD agents and CLI commands.

> Tip: Keep this README handy while working inside VS Code or terminal for quick reference.

---

Made with ⚡ for research & engineering excellence.

