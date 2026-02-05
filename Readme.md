# Functions, Tools, and Agents with LangChain

This repository explores modern capabilities of Large Language Models (LLMs) using LangChain, with a strong focus on function calling, tools, routing, and the LangChain Expression Language (LCEL).

The landscape of LLMs and supporting libraries is evolving rapidly. This project is designed to help you stay ahead by demonstrating how to build structured, reliable, and extensible LLM-powered applications using the latest LangChain patterns.

---

## What You’ll Learn

By working through these notebooks, you will learn how to:

* Generate structured outputs, including function calls, using LLMs
* Use LangChain Expression Language (LCEL) to simplify and customize chains and agents
* Apply function calling for tasks like tagging and data extraction
* Understand tool selection and routing using LangChain tools and LLMs
* Build functional conversational agents with clean, composable abstractions

---

## Repository Structure
```text 
├── L1-openai_functions.ipynb
├── L2-lcel.ipynb
├── L3-function-calling.ipynb
├── L4-tagging-and-extraction.ipynb
├── L5-tools-routing-apis.ipynb
└── L6-functional_conversation.ipynb
```

---

## Notebook Overview

### L1 – OpenAI Functions

Introduces OpenAI’s function calling capability and shows how LLMs can return structured outputs instead of plain text.

### L2 – LangChain Expression Language (LCEL)

Covers LCEL syntax and concepts, demonstrating how it simplifies chain composition and customization.

### L3 – Function Calling

Deep dive into using function calling with LangChain for controlled, reliable LLM interactions.

### L4 – Tagging and Extraction

Shows how to apply function calling for tagging, classification, and structured data extraction tasks.

### L5 – Tools, Routing, and APIs

Explains how LangChain tools work, how LLMs select tools, and how routing logic can be implemented.

### L6 – Functional Conversation

Builds a functional conversational agent that combines tools, routing, and function calls into a cohesive system.

---

## Prerequisites

* Python 3.9+
* Basic understanding of LLMs and prompt engineering
* Familiarity with Jupyter Notebooks
* An OpenAI API key (or compatible LLM provider)

---

## Setup

1. Clone the repository
   git clone [https://github.com/PrathameshLohar/Functions-Tools-and-Agents-with-LangChain.git](https://github.com/PrathameshLohar/Functions-Tools-and-Agents-with-LangChain.git)
   cd Functions-Tools-and-Agents-with-LangChain

2. Install dependencies
   pip install langchain openai jupyter

3. Set your API key
   export OPENAI_API_KEY="your_api_key_here"

4. Launch Jupyter
   jupyter notebook

---

## Who This Is For

* Developers building LLM-powered applications
* Engineers interested in structured LLM outputs
* Anyone learning LangChain agents, tools, and routing
* Practitioners looking to modernize their LLM workflows

---

## Notes

* The notebooks are designed to be followed in order
* Examples focus on clarity and learning rather than production optimization
* Concepts demonstrated here are foundational for advanced agentic systems

---

## License

This project is intended for educational purposes. Refer to the repository for licensing details.
