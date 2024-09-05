# What is LLM Benchmark
# Benchmark Category
There are 8 key LLM Benchmarks across the 4 most critical domains (Language Understanding, Reasoning, Coding, and Conversation). These benchmarks are widely utilized in industry applications and are frequently cited in technical reports. They include:

* **TruthfulQA** — Truthfulness
* **MMLU** — Language understanding
* **HellaSwag** — Commonsense reasoning
* **BIG-Bench Hard** — Challenging reasoning tasks
* **HumanEval** — Coding challenges
* **CodeXGLUE** — Programming tasks
* **Chatbot Arena** — Human-ranked ELO-based benchmark
* **MT Bench** — Complex conversational ability

![image](https://github.com/user-attachments/assets/4e4abbe2-e673-4f33-82f8-f0d76fc63e5f)
Source: [confident-ai.com](https://www.confident-ai.com/blog/llm-benchmarks-mmlu-hellaswag-and-beyond)

## LLM Benchmark Leaderboard

| Model | Multi-choice Qs <br> (MMLU) | Reasoning <br> (HellaSwag) | Python coding <br> (HumanEval) | Future Capabilities <br> (BBHard) | Grade school math <br> (GSM-8k) | Math Problems <br> (MATH) |
|---|---|---|---|---|---|---|
| Claude 3.5 Sonnet | 88.70% | 89.00% | 92.00% | 93.10% | 96.40% | 71.10% |
| Claude 3 Opus | 86.80% | 95.40% | 84.90% | 86.80% | 95.00% | 60.10% |
| Gemini 1.5 Pro | 81.90% | 92.50% | 71.90% | 84% | 91.70% | 58.50% |
| Gemini Ultra | 83.70% | 87.80% | 74.40% | 83.60% | 94.40% | 53.20% |
| GPT-4 | 86.40% | 95.30% | 67% | 83.10% | 92% | 52.90% |
| Llama 3 Instruct - 70B | 82% | 87% | 81.7% | 81.3% | 93% | 50.4% |
| Claude 3 Haiku | 75.20% | 85.90% | 75.90% | 73.70% | 88.90% | 38.90% |
| GPT-3.5 | 70% | 85.50% | 48.10% | 66.60% | 57.10% | 34.1% |
| Mixtral 8x7B | 70.60% | 84.40% | 40.20% | 60.76% | 74.40% | 28.40% |
| GPT-4o | 88.7% | - | 90.2% | - | - | 76.60% |
| GPT-4o mini | 82% | - | 87.00% | - | - | 70.20% |
| Llama 3 Instruct - 8B | 68.40% | - | 62% | 61% | 79.60% | 30% |
| Grok 1.5 | 73.00% | - | 63% | - | 62.90% | 23.90% |
| Mistral Large | 81.2% | 89.2% | 45.1% | - | 81% | 45% |
| Gemini 1.5 Flash | 78.90% | - | - | 89.20% | - | 67.70% |
| GPT-4T 2024-04-09 | 86.5% | - | - | 87.60% | - | 72.2% | 


| Capability | Benchmark | Description | Gemini Ultra | GPT-4 |  Claude 3.5  |  Claude  Sonnet |  Opus 3 |  Gemini 1.5 |  Gemini Ultra Pro |  GPT-3 |  Llama 70B |  Instruct 70B |  Haiku |  Claude 3 |  Mixtral 3.5 |  GPT-3.5 8xB |  GPT-4-0 |  GPT-40 mini |  Llama 3 8B |  Instruct 6B |  Mistral |  Grok 1.5 |  Large  |  Gemini 1.5 |  GPT-4T Flash |  GPT-4 2024-04-09 | 
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| **General** | MMLU | Representation of questions in 57 subjects (incl. STEM, humanities, and others) | 90.0% (CoT@32) | 86.4% (8-shot, reported) | 88.70% | 88.70% | 86.80% | 88.00% | 83.70% | 81.90% | 86.40% | 82% |  | 75.20% | 70.60% | 70% | 88.7% | 82% | 68.40% | 73.00% | 81.2% | 78.90% | 86.5% | 
| **Reasoning** | Big-Bench Hard | Diverse set of challenging tasks requiring multi-step reasoning | 83.6% (3-shot) | 83.1% (3-shot, (API)) | 89.00% | 89.00% | 95.40% | 95.00% | 92.60% | 87.80% | 95.30% | 87% |  | 85.90% | 85.50% | 84.40% | - | - | - | - | 89.2% | - | 89.2% | - |
|  | DROP | Reading comprehension (F1 Score) | 82.4 Variable shots | 80.9 (3-shot, reported) | 92.00% | 92.00% | 84.90% | 84.90% | 79.00% | 71.40% | 67% | 81.7% |  | 75.90% | 48.10% | 40.20% | 90.2% | 87.00% | 62% | 63% | 45.1% | - | 45.1% | - |
|  | HellaSwag | Commonsense reasoning for everyday tasks | 87.8% (10-shot) | 95.3% (10-shot, reported) | 93.10% | 93.10% | 86.80% | 86.80% | 84% | 83.60% | 83.10% | 81.3% | 73.70% | 73.70% | 66.60% | 60.76% | - | - | 61% | - | - | - | 89.20% | 87.60% |
| **Math** | GSM8K | Basic arithmetic manipulations (incl. grade school math problems) | 94.4% (maj@32) | 92.0% (5-shot CoT, reported) | 96.40% | 96.40% | 95.00% | 95.00% | 91.70% | 94.40% | 92% | 93% | 88.90% | 88.90% | 57.10% | 74.40% | - | - | 79.60% | 62.90% | 81% | - | 81% | - |
|  | MATH | Challenging math problems (high school algebra, pre-calculus, and others) | 53.2% (4-shot) | 52.9% (4-shot, API) | 71.10% | 71.10% | 60.10% | 60.10% | 58.50% | 53.20% | 52.90% | 50.4% | 38.90% | 34.1% | 28.40% | - | 76.60% | 70.20% | 30% | 23.90% | 45% | 67.70% | 72.2% |
| **Code** | HumanEval | Python code generation | 74.4% (0-shot, (T)) | 67.0% (0-shot, reported) | 92.00% | 92.00% | 71.90% | 71.90% | 74.00% | 74.00% | 67% | 81.7% | 79.90% | 75.90% | 40.20% | - | - | - | 62% | 63% | 45.1% | - | - | - |
|  | Natural2Code | Python code generation. New held out dataset, eval-like, not leaked on the web | 74.9% (0-shot) | 73.9% (0-shot, API) |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |








# Reference
* https://www.confident-ai.com/blog/llm-benchmarks-mmlu-hellaswag-and-beyond





