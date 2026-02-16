🧠 AI-Powered PDF-Based Machine Error Diagnosis System
📌 Overview

This project is an intelligent troubleshooting assistant that retrieves machine error solutions from PDF manuals using Natural Language Processing and a Transformer-based deep learning model. Users can describe issues in natural language, and the system returns the most relevant solution automatically.

⚙️ Technologies Used

Python

Sentence Transformers (MiniLM / BERT-based model)

PyTorch

pdfplumber (PDF text extraction)

NumPy / Regex (text processing)

🤖 Deep Learning Model

Transformer-based Sentence Embedding Model

Converts text into semantic vectors

Uses Cosine Similarity to find closest matching solution

🔄 System Workflow

Upload machine manual PDF

Extract and clean text

Split into error–solution chunks

Convert chunks into embeddings

Store embeddings as knowledge base

User enters error description

Convert query into embedding

Compare with stored vectors

Return most relevant solution

🧩 Core Logic

The system performs semantic search, not keyword matching.
Even if user wording differs from the PDF, the Transformer model understands meaning and retrieves the correct troubleshooting step.

🚀 Features

Natural language query support

Works with technical PDF manuals

Fast semantic similarity search

Lightweight academic prototype

Extendable for industrial automation

🎯 Use Cases

Machine troubleshooting assistant

Technical helpdesk automation

Industrial maintenance support

Smart document search systems

📊 Expected Output

User input: “network issue in machine”
System output:
Network connection lost – Check LAN cable and restart router
