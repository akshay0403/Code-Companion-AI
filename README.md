# Code-Companion-AI

# Overview
This repository contains code for an LLM-powered coding assistant built using the smolagents framework and Gradio for deployment. It demonstrates how lightweight agent architectures can be used to integrate LLMs with tools like search engines and code interpreters to deliver interactive, intelligent systems. The notebook offers a modular and reproducible setup suitable for experimentation and further extension.

# Abstract
This project explores the use of agent-based design patterns in building AI assistants that leverage large language models (LLMs) and real-time tools. Utilizing the smolagents library, it combines language understanding with utility tools (e.g., DuckDuckGo search) to answer programming questions, generate code, and assist users via a Gradio interface. The integration of LiteLLM and Google’s Generative AI provides flexible backend support for inference.

# Introduction
The aim is to develop an intelligent coding assistant that demonstrates how minimal agents, enhanced with search and code capabilities, can interactively solve user problems. By combining lightweight tooling and prompt-driven interactions, this project simulates how agents can be used in developer tools or educational platforms.

# Problem Statement
Develop a lightweight AI assistant capable of answering development-related queries, generating code, and utilizing web tools in real time—deployed through an accessible UI.

# Motivation
- **Agent-Based Interaction:** Showcase the potential of minimal autonomous agents in AI-powered systems.

- **LLM Utility:** Leverage the power of LLMs for dynamic question answering and code assistance.

- **Low Overhead Deployment:** Use tools like Gradio for rapid deployment and user feedback collection.

# Key Features
- **Agent Framework:** LiteLLMModel for LLM interactions

- **DuckDuckGoSearchTool:** for real-time search

- **CodeAgent:** to orchestrate tool usage based on user input

- **User Interface:** Gradio App for prompt input and agent output

# Future Enhancements
- Add memory and feedback loops to agents

- Support multi-modal input/output (e.g., voice, images)

- Deploy as a standalone web service or VSCode extension

- Integrate with vector databases for RAG-style workflows
