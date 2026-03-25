## RAG Example

### 1. Document Loading, Chunking - Prepare Knowledge base (Document Parser)
💡 Concept:
Load documents from various sources (text, PDF, web) and split them into manageable chunks for efficient retrieval and processing.

📄 Documents              🔢 Vectors          🤖 Response
Knowledge Base            HuggingFace          Context-Aware
Source Data          →    Free Embeddings  →   Generated Answer



### 2. Vector Store Creation 

💡 Concept:
Use HuggingFace's free embedding models (no API key required!) to convert text into vectors and store them in FAISS for fast similarity search.

all-MiniLM-L6-v2 :- Fast & Efficient (384 dims)

all-mpnet-base-v2 :- High Quality (768 dims)

multi-qa-MiniLM-L6 :- Q&A Optimized

e5-large-v2 :- SOTA Performance
