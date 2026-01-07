# Getting Started with LangChain

[![LangChain](https://img.shields.io/badge/LangChain-1.2+-blue)](https://docs.langchain.com/)[![Python](https://img.shields.io/badge/Python-3.13+-yellow)](https://www.python.org/)

##  Overview

This repository has some examples on how to build AI applications using LangChain, the leading frameworks for LLM application development.

## Requirements

- Python 3.13+ 
- Ollama local version(using docker)
- Jupyter Notebook


## Setup
 Use docker for running Ollama
 ```bash
   docker run -d -v ollama:/root/.ollama -p 11434:11434 --name ollama ollama/ollama
 ```
 Pull required model
 
```bash
 docker exec -it ollama ollama pull llama3.2:1b
```

## Examples

### Notebook 1 : Build First Chain
**Notebook**: [`notebooks/1.0_First_LangChain.ipynb`]
- LangChain 1.2
- Ollama Chat model

### Notebook 2 : LLM Chains
**Notebook**: [`notebooks/2.0_LLM_Chains.ipynb`]
- LangChain 1.2
- Ollama Chat model

### Notebook 2 : Create Simple Agents
**Notebook**: [`notebooks/3.0_LangChain_Create_Agents.ipynb`]
- LangChain 1.2
- Ollama Chat model
