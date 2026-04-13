# ASSIGNMENT-GenAI-Deep-Technical-Blog-on-LangChain

LangChain Blog Project: Blog Link: https://medium.com/@abutalhaparkote/langchain-building-modular-llm-applications-from-scratch-c66a18642ca2

Companion code for the technical blog "LangChain: Building Modular LLM Applications from Scratch."

A complete, hands-on implementation of every LangChain component — from basic LLM calls to a full RAG pipeline with memory — written as clean, well-commented Jupyter Notebooks.

# Project Structure
 # langchain-blog-project/
# ├── notebooks/
# │   ├── 01_llm_chatmodel.ipynb       # LLMs, Chat Models, streaming, batching
# │   ├── 02_prompt_templates.ipynb    # ChatPromptTemplate, few-shot prompting
# │   ├── 03_chains_lcel.ipynb         # LCEL pipes, sequential & parallel chains
# │   ├── 04_memory.ipynb              # Buffer, Window, Summary memory
# │   ├── 05_agents_tools.ipynb        # ReAct agents, custom tools, Wikipedia
# │   └── 06_rag_pipeline.ipynb        # Full RAG system with memory             
# ├── .env.example                     # API key template
# ├── requirements.txt
# └── README.md

 Quick Start
1. Clone the repo
bashgit clone https://github.com/YOUR_USERNAME/langchain-blog-project.git
cd langchain-blog-project
2. Create a virtual environment
bashpython -m venv venv
source venv/bin/activate        # Mac/Linux
venv\Scripts\activate           # Windows
3. Install dependencies
bashpip install -r requirements.txt
4. Set up your API key
bashcp .env.example .env
# Open .env and add your OPENAI_API_KEY
5. Launch Jupyter
bashjupyter notebook
Open the notebooks/ folder and run them in order.

 Notebooks Overview
NotebookTopics Covered01_llm_chatmodelInvoke, stream, batch, token usage02_prompt_templatesChatPromptTemplate, few-shot, variables03_chains_lcelPipe operator, sequential, parallel, Pydantic output04_memoryBuffer, Window (k=3), Summary memory05_agents_tools@tool decorator, ReAct agent, Wikipedia tool06_rag_pipelineLoad → split → embed → retrieve → answer → memory RAG

# Requirements

Python 3.10+
OpenAI API key (get one here)
~$0.05–0.10 in OpenAI credits to run all notebooks


# Related Blog
Read the full technical blog on Medium: [link here]

# Tech Stack

LangChain v0.3
OpenAI GPT-4o-mini
FAISS — vector store
LangSmith — optional observability

# Author
Parkote Abutalha
Intern at: Innomatics Research Labs
Intern ID: IN226113802

