# HR-Knowledge-assistant

## Project Overview
The Mini HR Knowledge Assistant is a Generative AI application that answers employee questions using uploaded HR documents such as leave policies, payroll policies, attendance policies, recruitment policies, and employee benefits.

## Technologies Used
- Python
- LangChain
- LangGraph
- ChromaDB
- Hugging Face Embeddings
- BM25
- Reciprocal Rank Fusion (RRF)
- Cross-Encoder Reranking
- Groq LLM

## Key Features
1. Upload multiple PDF, DOCX, and TXT documents.
2. Extract and process document content.
3. Generate embeddings and store them in ChromaDB.
4. Perform keyword and vector-based hybrid retrieval.
5. Rerank retrieved documents using a Cross-Encoder.
6. Generate context-based answers using an LLM.
7. Provide source citations.
8. Maintain conversational memory using LangGraph.

## Architecture
Document Upload → Text Extraction → Chunking → Embeddings → ChromaDB → Hybrid Retrieval → Reranking → LLM → Answer Generation.

## How to Run
1. Open the Google Colab notebook.
2. Install the required dependencies.
3. Add your Groq API key securely using Colab Secrets.
4. Upload HR documents.
5. Run the notebook cells in order.
6. Ask questions about the uploaded HR documents.

## Expected Outcome
An AI-powered HR assistant that provides relevant, context-based answers from uploaded company HR documents.
