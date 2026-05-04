Biz Optima: AI-Driven Business Advisory System

Project Overview
Biz Optima is an advanced AI system designed to provide high-level business insights and CFO-level advisory. By leveraging Retrieval-Augmented Generation (RAG), the system ensures that responses are grounded in a specialized knowledge base, including university-level business curricula and specific legal codes.

Tech Stack
Language:** Python
Framework:** LlamaIndex
AI Models:** Integration with LLM APIs (OpenAI/Anthropic)
Environment:** Developed in VS Code

Key Features
Custom Knowledge Retrieval:** Uses RAG to process and query specialized textbooks and legal documentation.
Data Integrity:** Specifically designed to reduce AI hallucinations by prioritizing local data sources.
Technical Troubleshooting:** Developed with a focus on clean, modular code and efficient data ingestion.

Repository Structure
`/data`: Contains the knowledge base (legal codes, textbooks).
`/scripts`: Main Python scripts for indexing and querying.
`requirements.txt`: Necessary libraries for setup.

Setup & Installation
1. Clone the repository.
2. Install dependencies: `pip install -r requirements.txt`.
3. Configure your API keys in a secure `.env` file.
4. Run the main script to start the advisory interface.

Security Focus
As a Cybersecurity-focused developer, I prioritized:
* Secure management of API environment variables.
* Data validation during the ingestion of OpenStax and legal files.
