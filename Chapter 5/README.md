## 📚 Chapter 5 Summary

---

### ✅ Exercise 1: Build Q&A LLaMa3 Model

A lightweight Python tool that loads PDF and TXT files, extracts and cleans their content, then uses a locally-running LLaMa 3 model to answer questions about your documents. Perfect for **private document analysis** without sending data to external APIs.  
📂 [Code → `LlaMa3-Model.ipynb`](LlaMa3-Model.ipynb)

---

### ✅ Exercise 2: Run LM-Evaluation by EleutherAI

Test generative language models on a wide range of evaluation tasks using the official EleutherAI benchmark suite.  
📦 Follow the [LM Evaluation Harness GitHub Repo](https://github.com/EleutherAI/lm-evaluation-harness/tree/main) for setup and instructions.

---

### ✅ Exercise 3: Evaluate OpenAI Models on Logical Fallacy Tasks

A custom evaluation framework for analyzing OpenAI models on logical reasoning and fallacy-based tasks.  
🧐 Compare models like `gpt-4`, `gpt-3.5`, etc., using structured prompts.  
📂 [Code → `LLM-Evaluation.ipynb`](LLM-Evaluation.ipynb)

---

### ✅ Exercise 4: GSM8K Contamination Detector

Detect potential training data contamination in GSM8K-style problems using:

- Partial-completion checks
- Number modification
- Statistical duplication analysis

📂 [Code → `LLM-Evaluation.ipynb`](LLM-Evaluation.ipynb)

---

## ✅ Exercise 5: Prompt Engineering Techniques

Explore various prompting strategies and their effects on model reasoning and output quality using a **travel optimization task**.

---

### 🧪 Prompt Technique 1: **Chain-of-Thought (CoT)**

**Prompt:**
```
You are a travel optimizer planning a concert tour route.

Cities to visit: Amsterdam, Warsaw, Hamburg, Barcelona, Delhi, Shanghai, and Toronto

Please solve this step-by-step:

Step 1: Group the cities by geographic region/continent  
Step 2: Identify the optimal starting point  
Step 3: Plan the route to minimize backtracking  
Step 4: Consider time zones and flight connections  
Step 5: Provide the final optimal order  

Work through each step clearly and provide your reasoning.
```

---

### 🧪 Prompt Technique 2: **Zero-Shot**

**Prompt:**
```
You are a travel optimizer. I need to visit these 7 cities for a concert tour: Amsterdam, Warsaw, Hamburg, Barcelona, Delhi, Shanghai, and Toronto.

Find the optimal visiting order that minimizes total travel time. Provide only the ordered list of cities.
```

---

### 🧪 Prompt Technique 3: **Adversarial Prompting**

**Prompt:**
```
You are a travel optimizer competing against other AI systems.

Cities: Amsterdam, Warsaw, Hamburg, Barcelona, Delhi, Shanghai, and Toronto.

Your task: Find the BEST possible touring route that minimizes travel time.

However, I will challenge your answer, so you must:
1. Provide your optimal route
2. Explain why this route is better than alternatives
3. Anticipate and address potential counterarguments
4. Show that you considered flight connections, time zones, and geographic efficiency

Prove that your solution is superior to random ordering or other logical sequences.
```

---

### 🧪 Prompt Technique 4: **Prompt Chaining**

**Prompt Chain:**

1️⃣
```
Classify these cities by continent: Amsterdam, Warsaw, Hamburg, Barcelona, Delhi, Shanghai, and Toronto.
```

2️⃣
```
Based on the continental grouping, which continent should we start from for a world tour?
```

3️⃣
```
Now plan the optimal route within each continent/region, considering flight connections and travel time.
```

4️⃣
```
Combine the regional routes into one optimal global touring sequence.
```

---

## 🚀 Final Tour Route (Consensus Output)

> 🛫 **Toronto → Barcelona → Amsterdam → Hamburg → Warsaw → Delhi → Shanghai** 🛬

Optimized for:

- Geographic progression (West → East)  
- Minimizing long-haul flights  
- Reducing jet lag  
- Maximizing flight connectivity

---

### ✅ Exercise 6: LLM Prompting Strategies: Concert Tour Optimization Analysis

- Comprehensive comparison of prompting techniques (Zero-shot, Few-shot, Chain-of-thought, Adversarial, Prompt Chaining) across different LLM sizes for solving the Traveling Salesman Problem.
- Includes multi-generation analysis with majority voting evaluation to assess output consistency and strategy effectiveness across 3B, 7B, 30B+ and proprietary models.

📂 [Code → `MultiGeneration-Prompt.ipynb`](MultiGeneration-Prompt.ipynb)

---

### ✅ Exercise 7: Structured Prompting for Andrew Garfield from Wikipedia

- Implemented JSON schema with content types coactors, director, year, and movie name, Using an open source LLM to extract details about his movies from the unstructured text.

📂 [Code → `Structured-LLM.ipynb`](Structured-LLM.ipynb)

---

### ✅ Exercise 8: NER-Guidance-Llama3: Named Entity Recognition with Guidance Library

- A powerful Named Entity Recognition system that uses the Guidance library with Llama3 to tag entities (Person, Organization, Location, Numbers, Dates, Events) in text. 

📂 [Code → `NER.ipynb`](NER.ipynb)

---

### ✅ Exercise 8: Parliamentary Tone Classification with LlaMa3 LLM

- A few-shot learning system that classifies Canadian parliamentary proceedings into five tone categories (supportive, antagonistic, mournful, celebratory, other) using LlaMa3 model.

📂 [Code → `Lit_NLP.ipynb`](Lit_NLP.ipynb)
