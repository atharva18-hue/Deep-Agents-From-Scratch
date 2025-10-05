#  Deep Agents from Scratch

 [![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python&logoColor=white)]()
 [![License](https://img.shields.io/badge/License-MIT-green)]()
 [![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter&logoColor=white)]()

## **Project Overview**

This project is a personal implementation of **advanced AI agents** built entirely from scratch. It demonstrates how to design and execute intelligent agents capable of **task planning, context management, and sub-agent delegation**. The system is inspired by modern AI research platforms and is structured to handle complex, multi-step workflows efficiently.

Key objectives of this project include:

- **Task Planning:** Agents can organize tasks into structured TODO lists, track progress, and manage multi-step workflows autonomously.
- **Context Management:** Agents maintain persistent state through a virtual file system, allowing them to remember information across tasks and sessions.
- **Sub-Agent Delegation:** Tasks can be split across multiple specialized sub-agents, ensuring efficient parallel execution and context isolation.
- **ReAct Loops:** The agents implement a Reason-Act loop framework, which forms the foundation for decision-making and problem-solving.
- **Extensibility:** The architecture is modular, allowing new tools or agent capabilities to be integrated easily.

The project includes Jupyter notebooks that progressively build a fully functional AI agent system, starting from simple task execution to advanced research agents capable of handling real-world research workflows.

By completing this project, one gains hands-on experience in **agent-oriented programming**, AI workflow management, and designing scalable intelligent systems.

 
 <img width="720" height="289" alt="Project Screenshot" src="https://github.com/user-attachments/assets/90e5a7a3-7e88-4cbe-98f6-5b2581c94036" />

 Personal implementation of **advanced AI agents** for task planning, context management, and sub-agent delegation. Fully built from scratch.

---

 ## **🚀 Quickstart**

 ### **Prerequisites**
 - Python 3.11 or later
 ```bash
 python3 --version
 ```
 - [uv package manager](https://docs.astral.sh/uv/)
 ```bash
 curl -LsSf https://astral.sh/uv/install.sh | sh
 export PATH="$HOME/.local/bin:$PATH"
 ```

---

 ## **Installation**
 ```bash
 # Clone this repository
 git clone https://github.com/atharva18-hue/Deep-Agents-From-Scratch.git
 cd Deep-Agents-From-Scratch
 
 # Install dependencies
 uv sync
 ```

---

 ## **Environment Setup**
 ```bash
 # Create .env file
 touch .env
 ```
 Add your API keys:
 ```env
 TAVILY_API_KEY=your_tavily_api_key_here
 ANTHROPIC_API_KEY=your_anthropic_api_key_here
 LANGSMITH_API_KEY=your_langsmith_api_key_here
 LANGSMITH_TRACING=true
 LANGSMITH_PROJECT=deep-agents-from-scratch
 ```
  Keep `.env` private. Do not push API keys to GitHub.

---

 ## **Running Notebooks**
 ```bash
 # Run Jupyter notebooks
 uv run jupyter notebook
 
 # Or manually activate virtual environment
 source .venv/bin/activate
 # Windows: .venv\Scripts\activate jupyter notebook
```
 
---

 ## **🔧 Features**
 - **Task Tracking:** Multi-step workflow automation  
 - **Agent Memory:** Persistent virtual file system  
 - **Parallel Sub-Agents:** Efficient multi-task handling  
 - **ReAct Loops:** Reason + Act framework  
 - **Extendable Design:** Add new modules or tools easily  

---

 ## **🎨 Visuals**
 <img width="720" height="289" alt="Agent Architecture" src="https://github.com/user-attachments/assets/90e5a7a3-7e88-4cbe-98f6-5b2581c94036" />
 
 Diagram shows agent flow: **task planning → context storage → sub-agent delegation → full agent execution**

---

 ## **⚡ Future Work**
 - Real-time web API integration  
 - Multi-agent collaboration  
 - Advanced evaluation metrics and monitoring  
 - Enhanced visualizations of agent decisions  

---

 ## **📂 Repository Structure**
```
Deep-Agents-From-Scratch/
 │
 ├─ notebooks/               
 │  ├─ 0_create_agent.ipynb
 │  ├─ 1_todo.ipynb
 │  ├─ 2_files.ipynb
 │  ├─ 3_subagents.ipynb
 │  ├─ 4_full_agent.ipynb
 │  └─ assets/
 │
 ├─ src/deep_agents_from_scratch/  
 │  ├─ __init__.py
 │  ├─ file_tools.py
 │  ├─ prompts.py
 │  ├─ research_tools.py
 │  ├─ state.py
 │  ├─ task_tool.py
 │  └─ todo_tools.py
 │
 ├─ pyproject.toml
 ├─ uv.lock
 ├─ .gitignore
 ├─ LICENSE
 └─ README.md
 ```

---


 ## **📝 Author**
 **Atharva Chavhan**  
 📧 Email: `8767242559@example.com`  
 🔗 LinkedIn: [linkedin.com/in/atharva18-hue](https://www.linkedin.com/in/atharva18-hue)  
 
 Personal project fully implemented from scratch to explore AI agent design patterns and workflows.

 ------
