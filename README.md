<p align="center"> <b>🧠 RAG-Driven Meeting Intelligence System</b> </p>
<p align="center"> <b>Using BERT Embeddings & Open-Source LLMs</b> </p>
<p align="center"> <b>Transform meeting transcripts into actionable insights using Retrieval-Augmented Generation [RAG]</b> </p>
🚀 Overview
This project is a RAG-based intelligent meeting assistant that allows users to query meeting transcripts using natural language.

It combines:
1. BERT embeddings for semantic understanding
2. Vector search for efficient retrieval
3. Open-source LLMs for contextual response generation
   
👉 Think of it as a ChatGPT for your meetings, grounded in your own data.

✨ Features
1. 🔍 Semantic search over transcripts
2. 💬 Natural language Q&A
3. 🧠 Context-aware responses (RAG pipeline)
4. 📄 Smart chunking of long transcripts
5. 👥 Speaker-based filtering (optional)
6. ⚡ Fast retrieval using vector databases



⚙️ Tech Stack
| Component    | Technology                   |
| ------------ | ---------------------------- |
| Embeddings   | BERT / Sentence Transformers |
| Vector Store | FAISS / ChromaDB             |
| LLM          | LLaMA / Mistral / Falcon     |
| Backend      | Python                       |
| Frameworks   | LangChain / Custom Pipeline  |
| Data Format  | JSON / Text                  |

📂 Project Structure
1. data/                 # Raw & processed transcripts
2. embeddings/           # Embedding generation
3. retriever/            # Retrieval logic
4. llm/                  # LLM inference
5. rag_pipeline/         # Core pipeline
6. utils/                # Helper functions
7. requirements.txt
8. README.md

🔧 Installation
git clone https://github.com/bishal-bit/RAG-Driven-Meeting-Intelligence-System-using-BERT-Embeddings-and-Open-Source-LLMs.git

cd RAG-Driven-Meeting-Intelligence-System-using-BERT-Embeddings-and-Open-Source-LLMs

pip install -r requirements.txt

🔄 Workflow
1. Input meeting transcript
2. Chunk text into smaller segments
3. Convert chunks → embeddings using BERT
4. Store embeddings in vector database
5. User submits query
6. Retrieve top-k relevant chunks
7. LLM generates final contextual answer

📊 Evaluation
1. Retrieval Accuracy (Top-K relevance)
2. Answer Faithfulness
3. Response Latency
4. Context Recall
   
🔮 Future Improvements
1. 🎥 Real-time meeting integration (Zoom / Teams APIs)
2. 🎙️ Speech-to-text pipeline
3. 🧠 Fine-tuned domain-specific LLM
4. 🌐 Knowledge graph integration
5. 👤 Personalized insights per participant

🙌 Acknowledgements
1. HuggingFace Transformers
2. FAISS / ChromaDB
3. Open-source LLM community


## 👤 Author

**Bishal Sarkar**  
Data Science @ IIT Guwahati  

Passionate about Machine Learning, RAG systems, and real-world AI applications.

- 🔗 GitHub: https://github.com/bishal-bit  
- 💼 LinkedIn: [https://linkedin.com/in/bishal-sarkar](https://www.linkedin.com/in/bishal-sarkar-b98106217/)  
- 📧 Email: bishal.sarkar2001@gmail.com
