# n8n Automations

A collection of AI-powered automation workflows built using **n8n**, **LLM APIs**, and external APIs & tools.

##  Overview

This project demonstrates how no-code/low-code automation can be combined with AI to build scalable and intelligent workflows.

Each automation is designed to reduce manual work and improve efficiency using event-driven pipelines.

---

## 📦 Automations

### 1. Order Processing System

**Flow:**
Airtable → Gemini AI → JavaScript Code Node(json conversion) → Gmail

**Description:**
Automatically processes customer orders stored in Airtable and generates professional email responses using Gemini AI, then sends them via Gmail.

**Features:**
- Reads orders from Airtable  
- Generates email subject and body using AI  
- Sends automated emails via Gmail  
- Fully automated workflow pipeline  

**Required Airtable Fields:**
- Order Number  
- Customer  
- Product  
- Quantity  
- Price  
- Date  
- Status  
- Email  

---

## ⚙️ Workflow Architecture
