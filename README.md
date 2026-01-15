# Agentic AI with LangChain and LangGraph

A comprehensive learning repository for mastering **Agentic AI** through the Coursera course "[Agentic AI with LangChain and LangGraph](https://www.coursera.org/learn/agentic-ai-with-langchain-and-langgraph)".

## Purpose

This repository documents my journey in learning and practicing advanced AI agent development. The focus is on:

- **Building intelligent agents** using LangChain and LangGraph frameworks
- **Creating reasoning and planning systems** with AI agents
- **Implementing reflection and reflexion mechanisms** for improved decision-making
- **Developing stateful AI workflows** that maintain context and state
- **Integrating external knowledge sources** to enhance agent capabilities

The repository serves as both a learning resource and a reference for building production-ready AI agents.

## Directory Structure

```
.
├── README.md                                           # This file
├── LICENSE                                             # License information
├── notebooks/                                          # Jupyter notebooks with lessons and labs
│   ├── LangGraph101 Building Stateful AI Workflows.ipynb
│   │   └── Introduction to LangGraph and stateful workflows
│   ├── Build Reasoning and Acting AI Agents with LangGraph.ipynb
│   │   └── Core concepts of reasoning and acting in AI agents
│   ├── lab - Building a Reflection Agent with LangGraph.ipynb
│   │   └── Hands-on lab: Implementing reflection mechanisms
│   └── lab - Building a Reflexion Agent with External Knowledge In.ipynb
│       └── Hands-on lab: Enhanced agents with external knowledge integration
└── notes/                                              # Personal notes and summary documents
```

### Notebooks Overview

1. **LangGraph 101: Building Stateful AI Workflows**
   - Foundational concepts of LangGraph
   - Creating and managing stateful workflows
   - Agent state and transitions

2. **Build Reasoning and Acting AI Agents with LangGraph**
   - ReAct (Reasoning and Acting) pattern
   - Tool integration and execution
   - Multi-step problem solving

3. **Building a Reflection Agent with LangGraph**
   - Self-reflection in AI agents
   - Evaluating and improving outputs
   - Iterative refinement loops

4. **Building a Reflexion Agent with External Knowledge**
   - Integrating external knowledge sources
   - Enhanced decision-making with external data
   - Building robust agent systems

## Setup Instructions

### Prerequisites

- Python 3.10 or higher
- pip package manager
- Jupyter Notebook or JupyterLab
- Git

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Akanksha-Pandey/Agentic-AI-with-LangChain-and-LangGraph.git
   cd Agentic-AI-with-LangChain-and-LangGraph
   ```

2. **Create a virtual environment:**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install required packages:**
   ```bash
   pip install --upgrade pip
   pip install langgraph langchain langchain-openai jupyter ipykernel
   ```

   For additional dependencies (e.g., for specific integrations):
   ```bash
   pip install -r requirements.txt  # if available
   ```

4. **Set up API keys:**
   
   Create a `api_keys.json` file in the root directory with your API keys:
   ```
   {
      "OPENAI_API_KEY" : "your_api_key_here"
   }
   ```

5. **Start Jupyter:**
   ```bash
   jupyter notebook
   # or for JupyterLab:
   jupyter lab
   ```

6. **Open and run notebooks:**
   - Navigate to the `notebooks/` directory
   - Start with `lab - LangGraph101 Building Stateful AI Workflows.ipynb`
   - Progress through notebooks in order for best learning experience

### Environment Variables

Create a `api_keys.json` file (or use your preferred secrets management) to store:
- `OPENAI_API_KEY` - For OpenAI API access
- Other API keys for external integrations

### Troubleshooting

**Kernel Issues:**
If Jupyter cannot find the Python kernel, reinstall ipykernel:
```bash
python -m ipykernel install --user --name agentic-ai --display-name "Agentic AI"
```

**Package Conflicts:**
Clear pip cache and reinstall:
```bash
pip cache purge
pip install --force-reinstall -r requirements.txt
```

## Learning Path

1. Start with foundational LangGraph concepts 
2. Learn reasoning and acting patterns
3. Practice with reflection agent implementation
4. Explore advanced patterns with external knowledge integration
5. Review personal notes for reinforced learning

## Key Concepts Covered

- **LangGraph**: Framework for building stateful AI workflows
- **Agents**: Autonomous systems that take actions based on reasoning
- **ReAct Pattern**: Interleaving reasoning and acting
- **Tool Use**: Integrating external tools for agent capabilities
- **Reflection**: Self-evaluation and improvement mechanisms
- **Reflexion**: Learning from past experiences with external knowledge
- **State Management**: Maintaining context across multiple interactions

## Resources

- [LangChain Documentation](https://python.langchain.com/)
- [LangGraph Documentation](https://langchain-ai.github.io/langgraph/)
- [Coursera Course](https://www.coursera.org/learn/agentic-ai-with-langchain-and-langgraph)
- [OpenAI API Documentation](https://platform.openai.com/docs)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author

Learning repository created for educational purposes as part of the Coursera Agentic AI course.