# n8n Automations

Collection of AI-powered and workflow automation projects built with n8n.

## Automations

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
