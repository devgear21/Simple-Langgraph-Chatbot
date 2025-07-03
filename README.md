                                                         AI Chatbot with LangGraph (Jupyter Notebook)

This project is a conversational **AI chatbot** built inside a Jupyter Notebook using the **LangGraph** library. 
It allows users to chat with an intelligent assistant powered by a language model, while maintaining structured memory and flow using LangGraph.


Features

Accepts natural-language user input
Uses a language model (via OpenRouter or OpenAI)
Maintains memory across turns using LangGraph nodes
Flow is defined as a **graph of logic steps**, not just plain code
Interactive chat inside a Jupyter Notebook


In this chatbot:

- Each **node** represents a step (e.g. receiving input, calling the model, storing memory).
- LangGraph handles the flow between nodes automatically.
- It helps manage **chat history**, **looping logic**, and **state transitions** clearly.
