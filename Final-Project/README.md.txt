# Final Course Project — Smart Personal Health Assistant AI Agent

Project GitHub Link : https://github.com/mohanyassen/MohanadYassin_Solo_ITAI2376/tree/main

## Overview

This is the final project for ITAI2376. It is a working AI agent implementation of a Smart Personal Health Assistant designed to help users track health information, receive personalized recommendations, and interact with an AI-driven assistant.

The system simulates an AI agent that uses reasoning, memory, and tools to respond to user inputs related to health and wellness.

---

# Problem Statement

Many individuals struggle with maintaining consistent health habits due to lack of guidance, tracking tools, and personalized feedback.

This AI agent is designed to help users by:

* Providing basic health and wellness advice
* Tracking simple user information
* Responding to health-related questions
* Simulating a personalized AI assistant experience

---

# Solution Overview

The system is a rule-based AI agent built in Python that simulates intelligent behavior using:

* User input processing
* Memory storage (JSON-based)
* Rule-based reasoning
* Tool-like functions (nutrition, advice, logging)

---

# Features

* Health and wellness Q&A system
* Basic nutrition information lookup
* User memory storage (e.g., weight tracking)
* Personalized responses based on stored data
* Simple command-line AI agent interface

---

# AI Agent Architecture

## Input Layer

* User text input via terminal

## Reasoning Engine

* Rule-based decision system
* Keyword-based interpretation of user intent

## Memory System

* Stores user data (e.g., weight, preferences)
* Implemented using JSON file storage

## Tools (Simulated)

* Nutrition lookup function
* Health advice generator
* User data logging system

## Output Layer

* Text-based AI responses in terminal

---

# Technologies Used

* Python
* JSON (memory storage)
* Rule-based AI logic
* Command-line interface
* AI agent design concepts (LangChain-inspired structure)

---

# Deep Learning Connection

Even though this implementation is rule-based, it connects to course deep learning concepts:

* **Transformers (Conceptual Use):** Inspired natural language understanding for user input interpretation
* **Embeddings (Conceptual):** Understanding meaning through structured input processing
* **AI Agent Design:** Combines reasoning, memory, and action modules similar to modern LLM agents

---

# Example Usage

**User:** I feel tired
**Agent:** You may need more rest. Try sleeping 7–9 hours and staying hydrated.

**User:** Calories in banana
**Agent:** A banana contains approximately 105 calories.

**User:** My weight is 180
**Agent:** Got it. I saved your weight in memory.

---

# How to Run the Project

1. Install Python 3.10+
2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Run the agent:

```bash
python main.py
```

---

# Project Structure

```text id="finalstructure"
Final-Project-Smart-Health-Agent/
│
├── main.py
├── src/
│   ├── agent.py
│   ├── tools.py
│   └── memory.py
├── memory.json
├── requirements.txt
├── README.md
└── demo/
```

---

# Limitations

* Rule-based system (not a full LLM-powered AI)
* Limited medical knowledge
* Simple memory storage
* No real-time API integration
* No deep learning model training in this version

---

# Future Improvements

* Integrate OpenAI GPT or similar LLM
* Add real health API integration
* Improve memory with vector databases
* Add voice input/output support
* Upgrade to multi-agent system architecture

---

# Key Learning Outcomes

Through this project, I learned:

* How AI agents are structured in real systems
* How memory and reasoning can be combined
* How to simulate intelligent behavior using Python
* How deep learning concepts connect to applied AI systems
* How to design and organize a full AI project

---

# Demo

(Add your video link here — YouTube, Loom, or Google Drive)

---

# Conclusion

This project demonstrates the application of AI agent design principles learned throughout ITAI2376, combining reasoning, memory, and structured logic into a functional assistant system.
