# IBM-Watson-Use-Cases

Exploring IBM Watson through hands-on use cases, applying AI solutions to real problems.

---

## Use Cases

### 1. Entity and Relation Extraction with RAG
Implemented a **Retrieval-Augmented Generation (RAG)** system for document search and entity relationship extraction using **IBM Watson NLU**.  
Relationships are stored in a database (**graph, vector, relational**), enabling context-aware answers beyond keyword matching.  
The system processes external articles from URLs, indexes them in a vector database, and answers user queries via **IBM WatsonX AI LLM**, referencing both document chunks and extracted relationships.  

**Tools:** IBM watsonx.ai RAG, IBM Watson Discovery, trafilatura, sentence_transformers, Milvus, Neo4j, PostgreSQL, IBM Db2  

---

### 2. Agentic AI – Automated Sick Leave Validation System
Built an **Agentic AI** in **IBM WatsonX Agent Lab** to automate medical certificate validation and leave requests.  
The agent extracts patient details and rest days, checks leave balances, provides recommendations for managers, and updates the database automatically.  

**Tools:** IBM watsonx.ai Agent Lab, LangChain, LangGraph, MemorySaver, requests, PostgreSQL  

---

### 3. Natural Language to SQL Query Generation (NL-to-SQL)
Developed an AI application converting natural language queries into optimized SQL using **IBM WatsonX LLM (granite-20b-code-base-sql-gen)** and translating results into human-readable responses.  
This enables business users to query databases without SQL knowledge, improving accessibility and speeding decision-making.  

**Tools:** IBM watsonx.ai ModelInference, Pandas, IBM Db2  
