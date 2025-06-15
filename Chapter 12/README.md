## 📚 Chapter 12 Summary

---

### ✅ Exercise 1: Chain-of-Notes (CoN) Prompting for RAG

- Implements a RAG system that demonstrates how Chain-of-Notes analysis helps identify when retrieved context lacks relevant information, preventing hallucinations by acknowledging knowledge gaps.

📂 [Code → `CoN-Prompting.ipynb`](CoN-Prompting.ipynb)

---

### ✅ Exercise 2: Cross-Encoder vs Bi-Encoder Comparison

- A comprehensive comparison between bi-encoders and cross-encoders for document retrieval, demonstrating how cross-encoders excel at nuanced queries while bi-encoders perform better on factual searches using iPhone Wikipedia data.

📂 [Code → `Cross-vs-Bi-Encoders.ipynb`](Cross-vs-Bi-Encoders.ipynb)

---

### ✅ Exercise 3: FLARE-Direct Implementation

- Implements Forward-Looking Active REtrieval (FLARE) that detects uncertainty in generated text and dynamically retrieves information to improve accuracy, demonstrated on Bollywood movie content generation.

📂 [Code → `FLARE-Direct.ipynb`](FLARE-Direct.ipynb)

---

### ✅ Exercise 4: GraphRAG with Entity Extraction

- Builds a graph-based RAG system that extracts entities and relationships from documents, enhancing retrieval through graph structure and entity relevance scoring for improved context understanding.

📂 [Code → `GraphRAG.ipynb`](GraphRAG.ipynb)

---

### ✅ Exercise 5: LLM-Embedder for Enhanced Retrieval

- Demonstrates the use of specialized LLM-Embedder model for creating high-quality document embeddings with instruction-aware encoding, improving retrieval accuracy for question-answering tasks.

📂 [Code → `llm-embedder.ipynb`](llm-embedder.ipynb)

---

### ✅ Exercise 6: Long Context Efficacy Testing

- Evaluates language model performance across varying context lengths to identify degradation patterns and optimal context windows for maintaining answer accuracy in long-document scenarios.

📂 [Code → `Long-Context.ipynb`](Long-Context.ipynb)

---

### ✅ Exercise 7: Mem0 Integration for Conversation Memory

- Implements persistent memory storage using Mem0 to maintain conversation context across sessions, enabling LLMs to recall user information and preferences for personalized interactions.

📂 [Code → `Mem0.ipynb`](Mem0.ipynb)
📂 [Result → `long_context_test_results.json`](long_context_test_results.json)

---

### ✅ Exercise 8: Query Likelihood Model (QLM) with Llama3

- Develops a Query Likelihood Model using Llama3 for document ranking, combining LLM-based relevance scoring with traditional overlap metrics for improved retrieval performance.

📂 [Code → `QLM-llama3.ipynb`](QLM-llama3.ipynb)

---

### ✅ Exercise 9: RankVicuna-Style Document Reranking

- Implements a two-stage retrieval system with initial bi-encoder retrieval followed by cross-encoder reranking, comparing default and custom prompt templates for question-answering tasks.

📂 [Code → `RankVicuna-Ranking.ipynb`](RankVicuna-Ranking.ipynb)

---

### ✅ Exercise 10: QA-Focused vs Generic Summarization

- Compares query-focused summarization techniques against generic approaches, demonstrating how QA-specific summarization removes noise and maintains relevant context for accurate answer generation.

📂 [Code → `Summerization-Methods.ipynb`](Summerization-Methods.ipynb)