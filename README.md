# 🧱 Deep Agents from Scratch

![Project Screenshot](https://github.com/user-attachments/assets/90e5a7a3-7e88-4cbe-98f6-5b2581c94036)

This is my personal implementation of **advanced AI agents** capable of task planning, context management, and sub-agent delegation.  
Built entirely from scratch for experimentation and learning.

---

## 🚀 Quickstart

### Prerequisites

- Python 3.11 or later
```bash
python3 --version
uv package manager

bash
Copy code
curl -LsSf https://astral.sh/uv/install.sh | sh
# Update PATH if needed
export PATH="$HOME/.local/bin:$PATH"
Installation
bash
Copy code
# Clone this repository
git clone https://github.com/atharva18-hue/Deep-Agents-From-Scratch.git
cd Deep-Agents-From-Scratch

# Install dependencies
uv sync
Environment Setup
Create a .env file in the project root:

env
Copy code
TAVILY_API_KEY=your_tavily_api_key_here
ANTHROPIC_API_KEY=your_anthropic_api_key_here
LANGSMITH_API_KEY=your_langsmith_api_key_here
LANGSMITH_TRACING=true
LANGSMITH_PROJECT=deep-agents-from-scratch
Note: Keep .env private. Do not push API keys to GitHub.

Running Notebooks
bash
Copy code
# Run Jupyter notebooks directly
uv run jupyter notebook

# Or activate virtual environment manually
source .venv/bin/activate  # Windows: .venv\Scripts\activate
jupyter notebook
📚 Project Overview
This repository contains 5 progressive notebooks, each building on the previous concepts:

Notebook	Focus
0_create_agent.ipynb	Setup ReAct agent loop
1_todo.ipynb	Task planning with TODO lists
2_files.ipynb	Virtual file system & agent memory
3_subagents.ipynb	Sub-agent delegation & context isolation
4_full_agent.ipynb	Complete research agent integration

🔧 Features
Task Planning: Organize complex workflows automatically

Virtual File System: Store and retrieve agent memory

Sub-agent Delegation: Handle parallel tasks with context isolation

ReAct Loops: Foundation for reasoning + acting agents

Modular Design: Add new tools and agents easily

🎨 Visuals


⚡ Future Work
Integrate with web APIs for real-time research tasks

Enable multi-agent collaboration

Implement advanced evaluation metrics

📝 Notes
This is a personal project, fully implemented from scratch to explore AI agent design patterns and workflows.
