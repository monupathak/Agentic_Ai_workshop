# Agentic_Ai_workshop
In this repo I shared the code and PPT that I used in Agentic Ai Workshop.

So the repo is basically a workshop project showing how to build and use agentic AI with LLMs in a practical way.

In short, the topics covered are:
- Getting free LLM API keys
  - Groq
  - Together AI
  - NVIDIA AI models
- Setting up a model using Python
- Using LangChain / LangGraph for agent workflows
- Creating a simple AI agent with state and reasoning
- Tool calling in agents
- Integrating external tools into an LLM agent
- Operations Research / logistics use case
- Using AI for routing and optimization problems like TSP (traveling salesman problem)
- Adding memory to agent conversations using SQLite checkpointer

What the code is showing:
- Installing Python libraries like:
  - langchain_community
  - langgraph-checkpoint-sqlite
  - langchain_groq
- Initializing a Groq LLM model
- Defining an AgentState for agent memory/state
- Building a LangGraph workflow
- Sending prompts/questions to the agent
- Binding tools to the model so it can call functions
- Defining a tool called solve_tsp_route that:
  - takes delivery locations
  - sends them to the OSRM routing API
  - computes the best route
  - returns total distance and optimal order
- Using a real-world operations research example for logistics:
  - depot
  - delivery points
  - route optimization
  - best sequence of stops
- Running the agent with a system prompt and memory session

So overall, this workshop is about:
- agentic AI basics
- LangGraph architecture
- LLM tool use
- real-world optimization use case in supply chain/logistics

The repo contains:
- one notebook: Agentic_ai.ipynb
- one PPT/PDF: AI for OR & Supply Chain-2.pdf

