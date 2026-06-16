# AI-Powered Email Assistant with RAG

**Flow:** Chat → Gemini AI Agent → Pinecone RAG Retrieval → Gmail Integration

**Description:**
An AI-powered email assistant that retrieves relevant email templates from Pinecone using RAG and sends personalized emails through Gmail based on natural language requests.

## Features

* Natural language email composition
* RAG-powered template retrieval
* Gmail integration for sending emails
* Powered by Gemini 2.5 Flash Lite
* Google Docs knowledge base
* Modular 3-workflow architecture

## Architecture

### 1. mails to pinecode

Google Docs → Text Chunking → Gemini Embeddings → Pinecone

### 2. mail agent pinecode

Chat Interface → RAG Retrieval → Gemini AI Agent

### 3. Send mail pinecone

Email Generation → Gmail API → Send Email

## Requirements

* n8n Instance
* Google Gemini API Key
* Pinecone Account
* Google Docs Access
* Gmail OAuth2 Credentials

## Technologies Used

* n8n
* Google Gemini 2.5 Flash Lite
* Pinecone Vector Database
* RAG (Retrieval-Augmented Generation)
* Gmail API
* Google Docs
