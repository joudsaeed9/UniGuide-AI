#  UniGuide AI

## Overview

UniGuide AI is an AI-powered university assistant that helps students find accurate answers to university-related questions using Retrieval-Augmented Generation (RAG).

Instead of relying only on the AI model's general knowledge, the system retrieves relevant information from university documents and then uses Google Gemini to generate accurate and reliable responses.

---

## Features

- Answer university-related questions.
- Retrieve information from university documents using RAG.
- Generate responses using Google Gemini.
- Human-in-the-Loop review before returning the final answer.
- Workflow management using LangGraph.

---

## Technologies Used

- Python
- Google Gemini
- LangChain
- ChromaDB
- Google Generative AI Embeddings
- LangGraph
- Google Colab

---

## Project Workflow

1. User enters a question.
2. The Retriever searches the university documents stored in ChromaDB.
3. Relevant information is retrieved.
4. Google Gemini generates an answer using the retrieved context.
5. A human reviewer approves or rejects the answer.
6. The approved answer is returned to the user.

---

## Project Structure

- Document Processing
- Embeddings Generation
- Chroma Vector Database
- Retriever
- LangChain Tool
- AI Agent
- LangGraph Workflow
- Human Review
- Memory Management

---

## Team Members

- Waad Alghamdi
- Joud Saeed

---

## Repository

https://github.com/joudsaeed9/UniGuide-AI
