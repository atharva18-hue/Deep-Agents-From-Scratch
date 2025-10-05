# 🧱 Deep Agents from Scratch

![Project Banner](https://github.com/user-attachments/assets/90e5a7a3-7e88-4cbe-98f6-5b2581c94036)

> Personal implementation of **advanced AI agents** for task planning, context management, and sub-agent delegation.  
> Fully built from scratch to experiment and explore AI workflows.

[![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python&logoColor=white)]()
[![License](https://img.shields.io/badge/License-MIT-green)]()
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter&logoColor=white)]()

---

##  Project Overview

This project demonstrates the design and implementation of AI agents capable of:

- **Task Planning:** Multi-step workflow management using TODO lists  
- **Virtual File System:** Store and retrieve agent memory efficiently  
- **Sub-agent Delegation:** Parallelize tasks while isolating context  
- **ReAct Loops:** Reasoning + acting agent foundation  
- **Modular & Extendable:** Easily integrate new tools and agents  

The project is structured in **5 progressive notebooks**, each building upon the previous:

| Notebook | Focus | Key Learnings |
|----------|-------|---------------|
| `0_create_agent.ipynb` | Agent initialization | Setup ReAct loop for reasoning + acting |
| `1_todo.ipynb` | Task planning | Track tasks, manage status, prevent drift |
| `2_files.ipynb` | Virtual file system | Store agent state, reduce token usage |
| `3_subagents.ipynb` | Sub-agent delegation | Context isolation, parallel workflows |
| `4_full_agent.ipynb` | Full research agent | Combine all modules into a production-ready agent |

---

##  Quickstart

### Prerequisites

- Python 3.11 or later
```bash
python3 --version

-----

uv package manager

curl -LsSf https://astral.sh/uv/install.sh | sh
# Update PATH if needed
export PATH="$HOME/.local/bin:$PATH"

