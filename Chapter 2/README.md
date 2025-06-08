## 📚 Chapter 2 Summary

---

### ✅ Exercise 1: Word Frequency Analysis on C4 (`realnewslike` Subset)

Analyze word frequencies after removing stop words from the C4 dataset to understand common language patterns.  
🔗 [Notebook: Word-Frequency.ipynb](Word-Frequency.ipynb)

---

### ✅ Exercise 2: Dataset Quality Analysis Scripts

Includes:

- Word frequency analysis  
- Topic representation and diversity  
- Factual error detection  
- Prompt quality evaluation  

Use these scripts to examine dataset characteristics, surface quality issues, and enhance prompt generation for better synthetic data.  
🔗 [Notebook: Quality-Synthetic-Dataset.ipynb](Quality-Synthetic-Dataset.ipynb)

---

### ✅ Exercise 3: Web Text Extraction Techniques

A detailed comparison of web text extraction techniques. Highlights why simple HTML parsing is insufficient and showcases advanced heuristics needed for high-quality content extraction.  
🔗 [Notebook: Remove-Web-Boilerplate.ipynb](Remove-Web-Boilerplate.ipynb)

---

### ✅ Exercise 4: C4 Non-English Text Detection

Detects non-English fragments in the English C4 subset using `langdetect`, revealing multilingual noise and mixed-language artifacts. Also investigates if these provide useful context for multilingual LLM training.  
🔗 [Notebook: Non-English-Text.ipynb](Non-English-Text.ipynb)

---

### ✅ Exercise 5: FastText-Based Quality Classifier

A lightweight classifier trained to distinguish between high-quality (Wikipedia) and low-quality (C4) web text. Achieves 75–85% accuracy and can be used for filtering or ranking content based on quality.  
🔗 [Notebook: Quality_Classifier_Document.ipynb](Quality_Classifier_Document.ipynb)
> Running on Colab Free Tier so couldn't load the actual datasets due to limited disk size.

---

### ✅ Exercise 6: Text Perplexity Analysis with KenLM

Trains a KenLM model to explore how perplexity varies across text types (e.g., formal writing, slang, SEO spam). Uses perplexity as a proxy for text quality and includes helpful visualization tools.  
🔗 [Notebook: Perplexity_Model.ipynb](Perplexity_Model.ipynb)
> Running on Colab Free Tier so couldn't load the actual datasets due to limited disk size.

---

### ✅ Exercise 7: Privacy Attacks on LLMs

Analyze privacy vulnerabilities in large language models, including memorization of personal information. Follow the instructions in the repo’s README to reproduce results.  
🔗 [GitHub Repo](https://github.com/jeffhj/LM_PersonalInfoLeak)

---

### ✅ Exercise 8: PII Detection in Web Text

Demonstrates methods for detecting personal identifiers (e.g., Gmail addresses) in large-scale web datasets. While scalable techniques are shown, full execution may require extensive compute resources.  
🔗 [Notebook: PII-Detection.ipynb](PII-Detection.ipynb)