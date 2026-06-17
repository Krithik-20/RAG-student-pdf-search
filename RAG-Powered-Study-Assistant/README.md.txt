RAG-Powered Study Assistant

## Overview
This project is a Retrieval-Augmented Generation (RAG) based Study Assistant built using Flowise.

It allows users to ask questions from PDF study materials and get AI-generated answers with context.

## Features
- PDF Parsing
- Text Chunking
- Embeddings using HuggingFace
- Vector Store (In-Memory)
- Retrieval-based QA
- Gemini AI responses

## Tech Stack
- Flowise
- Google Gemini 2.5 Flash
- HuggingFace Embeddings
- In-Memory Vector Store

## Workflow
PDF → Splitter → Embeddings → Vector Store → Retriever → Gemini → Answer

## Output
User asks question → AI answers from PDF content