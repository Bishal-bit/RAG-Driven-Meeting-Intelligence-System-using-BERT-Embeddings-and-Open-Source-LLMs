🧠 RAG-Driven Meeting Intelligence System
Using BERT Embeddings & Open-Source LLMs
<p align="center"> <b>Transform meeting transcripts into actionable insights using Retrieval-Augmented Generation</b> </p>
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

🏗️ Architecture
![Uploading mermaid-diagram.png…]()

flowchart TD
```mermaid
flowchart TD
    A[Meeting Transcripts] --> B[Text Chunking]
    B --> C[BERT Embeddings]
    C --> D[Vector Database (FAISS/Chroma)]
    D --> E[Retriever]

    Q[User Query] --> E
    E --> F[Relevant Chunks]
    F --> G[Open Source LLM (LLaMA/Mistral)]
    G --> H[Final Answer]
```

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
├── data/                  # Raw & processed transcripts
├── embeddings/           # Embedding generation
├── retriever/            # Retrieval logic
├── llm/                  # LLM inference
├── rag_pipeline/         # Core pipeline
├── utils/                # Helper functions
├── app.py                # Entry point
├── requirements.txt
└── README.md

🔧 Installation
git clone https://github.com/bishal-bit/RAG-Driven-Meeting-Intelligence-System-using-BERT-Embeddings-and-Open-Source-LLMs.git
cd RAG-Driven-Meeting-Intelligence-System

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
