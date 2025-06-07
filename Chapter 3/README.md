## 📚 Chapter 3 Summary

---

### ✅ Exercise 1: GPT Tokenizer Vocabulary Comparison — `o200k_base` vs `cl100k_base`

This project compares the vocabularies of OpenAI’s `o200k_base` (used in GPT-4o) and `cl100k_base` (used in GPT-3.5/4) tokenizers to highlight key differences in token distribution and language support.

Key findings:
- `o200k_base` has a doubled vocabulary size (200k tokens).
- Substantial improvements in multilingual support, especially for non-Latin scripts.
- More efficient token compression for international languages.
- Removal of redundant or less-used tokens from `cl100k_base`.
- Tokens are categorized by type to reveal structural and semantic changes.

🔗 [Notebook: Different-Vocabularies.ipynb](Different-Vocabularies.ipynb)

---

### ✅ Exercise 2: Byte Pair Encoding (BPE) Tokenizer from Scratch

A custom BPE tokenizer built and trained from scratch on domain-specific content (OpenWebText, due to removal of original OLM/Wikipedia dataset). This implementation aims to explore how domain-specific training affects vocabulary granularity and token efficiency.

Highlights:
- Full implementation of the BPE algorithm.
- Trained on technical/machine learning content.
- Compared vocabulary and token efficiency against GPT-2 and BERT tokenizers.
- Analyzes how well the tokenizer handles technical terms and compound expressions.

🔗 [Notebook: BPE-Implementation.ipynb](BPE-Implementation.ipynb)