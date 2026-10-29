# Python Class: Python + LLM Engineering

This repository is a practical training repo for learning Python fundamentals and building AI/LLM-powered agent systems.

## Structure

```text
0-python/                     Python fundamentals and data engineering
  01_Variables_Types.ipynb
  02_Conditions_Loops.ipynb
  03_Functions_DataStructures.ipynb

3-agent-simple/              Progressive AI agent exercises
  README.md
  agent_evolution/
    1/
      prompt_anatomy_agent_brain_no_hands.ipynb
    2/
      agent_postgres_tool.ipynb
    3/
      agent_pinecone_semantic_memory.ipynb
```

## What you'll learn

- Python variables, types, control flow, and functions
- Data structures for working with model inputs and outputs
- HTTP requests, JSON handling, and async patterns
- LLM prompt construction using f-strings and structured data
- Building a simple SQL-capable AI agent step by step
- Extending the agent with schema lookup, validation, and memory

## Setup

```bash
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate
pip install -r requirements.txt
jupyter lab
```

## Environment variables

Copy `.env.example` to `.env` and set your keys.

```bash
cp .env.example .env
```

## Notes

This repository is designed for learning by doing. Each notebook is intentionally incremental and builds on the previous one.
