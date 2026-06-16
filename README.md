<p align="center">
  <img src="https://raw.githubusercontent.com/n8n-io/n8n/master/assets/n8n-logo.png" alt="n8n logo" width="120" />
</p>

<h1 align="center">
  ⚡ n8n Automations
</h1>

<p align="center">
  <em>🤖 AI-powered · 🔁 Workflow automation · 🧩 Built with n8n</em>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/n8n-0.234.0-green?logo=n8n&logoColor=white&style=for-the-badge" alt="n8n version" />
  <img src="https://img.shields.io/badge/AI_Ready-✅-blue?style=for-the-badge" alt="AI Ready" />
  
  <img src="https://img.shields.io/badge/PRs-Welcome-brightgreen?style=for-the-badge" alt="PRs Welcome" />
</p>

<p align="center">
  <i>✨ Collection of AI-powered and workflow automation projects built with n8n ✨</i>
</p>

<hr />


### 1. Order Processing System

**Flow:** Airtable → Gemini AI → JavaScript Code Node (JSON Conversion) → Gmail

**Description:** Automatically processes customer orders stored in Airtable and generates professional email responses using Gemini AI, then sends them via Gmail.

#### Features
- Reads orders from Airtable
- Generates email subject and body using AI
- Sends automated emails via Gmail
- Fully automated workflow pipeline

#### Required Airtable Fields
- Order Number
- Customer
- Product
- Quantity
- Price
- Date
- Status
- Email

---

### 2. Tesla Financial Reports RAG Chatbot

**Flow:** Chat Trigger → AI Agent → Gemini AI → Pinecone Vector Store → Memory → Gmail

**Description:** An AI-powered chatbot that analyzes Tesla's Q3 and Q4 financial reports using Retrieval-Augmented Generation (RAG). It retrieves relevant information from a Pinecone vector database and generates accurate, context-aware responses with Gemini AI.

#### Features
- Interactive AI chatbot interface
- Answers questions about Tesla Q3 and Q4 earnings reports
- Retrieves information using Pinecone vector search
- Maintains conversation context with memory
- Generates concise, fact-based responses using Gemini AI
- Provides financial insights and report analysis

#### Technologies Used
- Google Gemini AI
- Pinecone Vector Database
- n8n AI Agent
- Memory Buffer
- Gmail Integration
- Retrieval-Augmented Generation (RAG)

---

### 3. Automated Document Ingestion to Pinecone

**Flow:** Google Drive Trigger → Download File → Extract PDF Content → Text Splitter → Gemini Embeddings → Pinecone Vector Store

**Description:** Automatically monitors a Google Drive folder for new PDF documents, extracts their content, converts the text into vector embeddings using Gemini AI, and stores them in Pinecone for semantic search and AI-powered retrieval.

#### Features
- Monitors a Google Drive folder for newly uploaded files
- Automatically downloads PDF documents
- Extracts text from PDF files
- Splits documents into optimized chunks
- Generates embeddings using Gemini AI
- Stores vectors in Pinecone for semantic search
- Fully automated document indexing workflow

#### Requirements
- Google Drive Folder
- PDF Documents
- Google Gemini API
- Pinecone Index

#### Technologies Used
- Google Drive
- Google Gemini Embeddings
- Pinecone Vector Database
- PDF Text Extraction
- Recursive Character Text Splitter
- n8n Automation

### 4. AI-Powered n8n Workflow Builder with RAG

**Flow:** Chat Trigger → Claude Opus 4 Agent → Pinecone RAG Retrieval → n8n API → Workflow Creation

**Description:**
Generates complete n8n workflows from natural language prompts using Claude Opus 4 and Pinecone RAG. The workflow automatically creates the generated automation in n8n and returns a direct workflow link.

## Features

* Converts plain English into n8n workflows
* Uses RAG for workflow examples and best practices
* Automatically creates workflows via the n8n API
* Returns a direct workflow URL
* Generates valid, importable n8n JSON

## Requirements

* n8n Instance
* Anthropic API Key
* OpenAI API Key
* Pinecone Index
* Google Drive Folder (RAG training data)

## Technologies Used

* n8n
* Claude Opus 4
* Pinecone
* OpenAI Embeddings
* Google Drive
* RAG (Retrieval-Augmented Generation)

### 5. AI-Powered Email Assistant with RAG

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


### 6. AI-Powered Email Assistant

**Flow:** Chat → Gemini AI Agent → Gmail Integration

**Description:**
A conversational email assistant that drafts and sends professional emails through Gmail using natural language commands.

## Features

* Natural language email composition
* Direct Gmail integration
* Powered by Google Gemini
* Professional email formatting with automatic signature
* Conversation memory for context

## How It Works

1. User sends a natural language request via chat
2. Gemini generates a professional email
3. Email is automatically sent through Gmail
4. User receives a confirmation message

## Requirements

* n8n Instance
* Google Gemini API Key
* Gmail Account with OAuth2

## Technologies Used

* n8n
* Google Gemini Chat Model
* Gmail API
* Buffer Window Memory



