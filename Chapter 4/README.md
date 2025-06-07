## 📚 Chapter 4 Summary

---

### ✅ Exercise 1: Word Context Analysis

This project demonstrates how word meanings can be inferred purely from contextual usage. By analyzing the word *"nervous"* and its synonyms across multiple corpora using NLTK and statistical methods, it reveals how surrounding words and grammatical patterns indicate semantic relationships — mimicking human language acquisition.  
🔗 [Notebook: Word-Context.ipynb](Word-Context.ipynb)

---

### ✅ Exercise 2: GPT-4o Crossword Clue Solver

A LangChain-based tool designed to evaluate GPT-4o’s ability to solve crossword puzzle clues.

Key features:
- Uses logprobs to assess model confidence.
- Identifies potentially dangerous failure cases (e.g., low confidence on correct answers or high confidence on incorrect ones).
- Provides a framework for qualitative LLM evaluation using real-world tasks.  
🔗 [Notebook: Crossword-Puzzle.ipynb](Crossword-Puzzle.ipynb)

---

### ✅ Exercise 3: Advanced Masking Strategies for Language Model Pretraining

Implements and compares multiple token masking techniques for transformer training, including:

- **MLM** (Masked Language Modeling)
- **PLM** (Permutation Language Modeling)
- **FLM** (Full Language Modeling)

Includes:
- Random, frequency-based, POS-aware, and span-based masking
- Configurable masking ratios and heuristics
- Tools to explore impact on downstream learning efficiency  
🔗 [Notebook: Masking-Algorithms.ipynb](Masking-Algorithms.ipynb)

---

### ✅ Exercise 4: Improved Chess AI — Scaling Language Models for Strategic Gameplay

A PyTorch-based training pipeline that scales GPT-style models to play chess strategically.

Highlights:
- Trains models from scratch using synthetic and real high-rated chess games.
- Applies improved tokenization and curriculum learning strategies.
- Larger models trained on 200K+ rated games achieved **40–65% win rates vs. Stockfish**.
- Demonstrates how data quality, model size, and training strategy improve performance in structured decision-making tasks.  
🔗 [Notebook: Chess.ipynb](Chess.ipynb)