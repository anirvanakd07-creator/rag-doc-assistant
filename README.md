📄 RAG Document Assistant

A Retrieval-Augmented Generation (RAG) based AI system that answers questions from documents using semantic search and LLMs.

🚀 Features
📚 Load and process PDF documents
🔍 Semantic search using embeddings
🧠 Context-aware answer generation
📝 Automatic summarization of documents

🛠 Tech Stack
Python
LangChain
ChromaDB (Vector Database)
HuggingFace Transformers
Sentence Transformers

⚙️ How it Works
Load PDF documents
Split into chunks
Convert text into embeddings
Store in vector database
Retrieve relevant chunks
Generate answer using LLM

📂 Project Structure
rag-doc-assistant/
│
├── sample_docs/
│   └── rpa_blueprism.pdf
│
├── rag_pipeline.ipynb
├── README.md

💡 Example Queries
What is RPA?
Explain Blue Prism
Summarize the document

📌 Future Improvements
Add web interface (Streamlit)
Support multiple documents
Use advanced LLM APIs

👨‍💻 Author
Anirvan Mohapatra
