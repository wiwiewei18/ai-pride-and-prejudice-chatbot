# Chatbot Project: Pride and Prejudice Assistant

## Overview

This project is a chatbot designed to answer questions and engage in discussions about **Jane Austen's "Pride and Prejudice"** using the LangChain framework. It leverages natural language processing to provide insightful and accurate responses about characters, themes, quotes, and much more from this classic novel.

---

## Tech Stack

- **LangChain**: Framework for building conversational AI applications.
- **Gemini API**: Language model for generating responses.
- **Python**: Programming language for implementing logic.
- **Gradio**: For creating a user-friendly chatbot interface.

---

## Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/wiwiewei18/ai-pride-and-prejudice-chatbot.git
   cd ai-pride-and-prejudice-chatbot
   ```

2. **Set Up Virtual Environment**

   ```bash
   python -m venv .venv
   source .venv/Scripts/activate
   ```

3. **Install Dependencies**

   ```bash
   pip install -r requirements.txt
   ```

4. **Add API Keys**  
   Create a `.env` file in the root directory and add your OpenAI API key:
   ```env
   GOOGLE_API_KEY=your_openai_api_key
   ```

---

## Implementation Details

- **LangChain Pipelines:**  
  The chatbot is built using LangChain’s conversational pipeline, combining retrieval-based and generative capabilities to answer questions accurately.

- **Context Awareness:**  
  A custom knowledge base is generated from text data of the novel to ensure responses stay relevant to "Pride and Prejudice."
