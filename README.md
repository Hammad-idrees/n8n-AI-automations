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

### 7. AI-Powered Email Automation – Filtering Messages & Auto-Replying

**Flow:** Schedule Trigger → Gmail → Gemini AI → Gmail

**Description:** Automatically monitors incoming emails, analyzes their content using Gemini AI, generates concise summaries with action items, and delivers a professionally formatted email report to designated recipients.

### Features

- Fetches emails received in the last 24 hours
- Organizes and processes email metadata automatically
- Uses Gemini AI to summarize email conversations
- Extracts key insights and action items
- Generates professional HTML email reports
- Sends automated summaries via Gmail
- Runs on a customizable daily schedule

### Required Configuration

#### Gmail
- Gmail OAuth Credentials
- Sender Email Account
- Recipient Email Address(es)

#### Gemini AI
- Google Gemini API Key
- Gemini Model Selection

#### Workflow Settings
- Schedule Time
- Email Query Filters
- Report Recipients

### Output

The workflow automatically generates:

- Email summaries
- Important discussion points
- Actionable tasks and follow-ups
- Structured HTML reports
- Daily inbox activity reports

### 8. Automated Sponsorship Email Detection & Reply System

**Flow:** Gmail Trigger → AI Agent → Sponsorship Detection → OpenAI → Gmail Reply

**Description:** Automatically monitors incoming emails, identifies sponsorship inquiries using AI, generates personalized sponsorship responses based on predefined pricing and collaboration terms, and sends replies directly through Gmail.

### Features

- Monitors incoming Gmail messages in real-time
- Detects sponsorship-related emails using AI
- Filters non-sponsorship emails automatically
- Generates professional sponsorship responses
- Includes predefined sponsorship pricing and terms
- Sends automated email replies via Gmail
- Eliminates manual screening of sponsorship requests

### Workflow Steps

1. Gmail Trigger detects new incoming emails.
2. Email content is extracted and formatted.
3. AI analyzes whether the email is a sponsorship inquiry.
4. Non-sponsorship emails are ignored automatically.
5. Sponsorship emails are passed to OpenAI.
6. A personalized response is generated based on sponsorship terms.
7. Gmail sends the reply directly to the sender.

### Required Configuration

#### Gmail
- Gmail OAuth Credentials
- Gmail Trigger Setup
- Reply Permissions

#### OpenAI
- OpenAI API Key
- GPT Model Configuration

#### Sponsorship Details
- Channel Information
- Sponsorship Pricing
- Collaboration Conditions
- Brand Acceptance Criteria

### Output

The workflow automatically provides:

- Sponsorship inquiry classification
- AI-generated sponsorship responses
- Automated Gmail replies
- Consistent pricing communication
- Professional sponsor engagement

---

### 9. WhatsApp AI Personal Assistant Automation

Flow: WhatsApp Trigger → AI Agent → OpenAI GPT-4o Mini → Memory Buffer → Tools (Wikipedia, Calculator, Gmail) → WhatsApp Response

Description: An AI-powered WhatsApp assistant built with n8n that automatically receives user messages, understands requests, maintains conversation history, provides intelligent responses, performs calculations, retrieves information, and sends emails when required.

Features

- Receives WhatsApp messages automatically
- Uses OpenAI GPT-4o Mini for intelligent conversations
- Maintains chat history using memory buffer
- Answers factual queries using Wikipedia integration
- Performs mathematical calculations using AI tools
- Generates and sends emails through Gmail
- Replies directly to users through WhatsApp Business Cloud API
- Fully automated AI assistant workflow

Technologies Used

- n8n Automation Platform
- OpenAI GPT-4o Mini
- WhatsApp Business Cloud API
- AI Agent
- Memory Buffer
- Wikipedia API
- Calculator Tool
- Gmail Integration

---
### 10. Telegram AI Assistant with Web Search Automation

Flow: Telegram Trigger → AI Agent → OpenAI GPT-4o → Memory Buffer → Tools (Search Sub-Workflow, Calculator) → Telegram Response

Description: An intelligent Telegram AI assistant built with n8n that automatically processes user messages, understands queries using OpenAI GPT-4o, maintains conversation context, performs calculations, executes web searches, and delivers AI-generated responses directly through Telegram.

Features

- Receives and processes Telegram messages automatically
- Uses OpenAI GPT-4o for natural language understanding
- Maintains session-based conversation history using memory buffer
- Supports multi-turn conversations with context retention
- Performs mathematical calculations using AI tools
- Searches the web using Hacker News, Wikipedia, and SerpAPI integrations
- Handles complex research queries through AI sub-workflow architecture
- Uses external tools dynamically through AI Agent
- Provides real-time AI-generated responses in Telegram
- Fully automated end-to-end AI assistant workflow

Technologies Used

- n8n Automation Platform
- OpenAI GPT API
- Telegram Bot API
- AI Agent (LangChain)
- Window Buffer Memory
- Sub-Workflow Architecture
- Hacker News API
- Wikipedia API
- SerpAPI (Google Search)
- Calculator Tool

---
