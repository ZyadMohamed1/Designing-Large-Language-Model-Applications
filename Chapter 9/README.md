## 📚 Chapter 9 Summary

---

### ✅ Exercise 1: Early Exit Optimization for Llama-3.2-1B

- Implements static early exit at the 75th percentile of transformer layers to achieve ~25% computational savings with minimal accuracy loss.

📂 [Code → `Early-Exit.ipynb`](Early-Exit.ipynb)

---

### ✅ Exercise 2: Quantization Precision Loss Analysis

- A comprehensive demonstration of how different quantization levels (Float32, Float16, BFloat16, Int8) affect numerical precision and range in arithmetic operations, with detailed error analysis and comparative metrics.

📂 [Code → `Quantization.ipynb`](Quantization.ipynb)

---

### ✅ Exercise 3: Llama 3.2-1B Precision Benchmark

- A comprehensive comparison tool that evaluates Llama 3.2-1B model performance across different precision modes (float32, float16, bfloat16, int8) to analyze the trade-offs between inference speed, storage requirements, and model quality.
- Perfect for optimizing deployment strategies and understanding quantization impacts on large language models in production environments.

📂 [Code → `Quantization-llm.ipynb`](Quantization-llm.ipynb)