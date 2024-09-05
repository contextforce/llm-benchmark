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


You are right! I missed the % symbol again. My apologies! 

Here is the table with the % symbol included in all evaluation scores:

| Capability | Benchmark | Description | Gemini Ultra | GPT-4 | Claude 3.5 | Claude Sonnet | Opus 3 | Gemini 1.5 | Gemini Ultra Pro | GPT-3 | Llama 70B | Instruct 70B | Haiku | Claude 3 | Mixtral 3.5 | GPT-3.5 8xB | GPT-4-0 | GPT-40 mini | Llama 3 8B | Instruct 6B | Mistral | Grok 1.5 | Large | Gemini 1.5 | GPT-4T Flash | GPT-4 2024-04-09 | 
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| General | MMLU | Representation of questions in 57 subjects (incl. STEM, humanities, and others) | 90.0% | 86.4% | 88.7% | 88.7% | 86.8% | 88.0% | 83.7% | 81.9% | 86.4% | 82% |  | 75.2% | 70.6% | 70% | 88.7% | 82% | 68.4% | 73.0% | 81.2% | 78.9% | 86.5% |  |  | 
| Reasoning | Big-Bench Hard | Diverse set of challenging tasks requiring multi-step reasoning | 83.6% | 83.1% | 89.0% | 89.0% | 95.4% | 95.0% | 92.6% | 87.8% | 95.3% | 87% |  | 85.9% | 85.5% | 84.4% | - | - | - | - | 89.2% | - | 89.2% | - | 
|  | DROP | Reading comprehension (F1 Score) | 82.4% | 80.9% | 92.0% | 92.0% | 84.9% | 84.9% | 79.0% | 71.4% | 67% | 81.7% |  | 75.9% | 48.1% | 40.2% | 90.2% | 87.0% | 62% | 63% | 45.1% | - | 45.1% | - | 
|  | HellaSwag | Commonsense reasoning for everyday tasks | 87.8% | 95.3% | 93.1% | 93.1% | 86.8% | 86.8% | 84% | 83.6% | 83.1% | 81.3% | 73.7% | 73.7% | 66.6% | 60.76% | - | - | 61% | - | - | - | 89.2% | 87.6% | 
| Math | GSM8K | Basic arithmetic manipulations (incl. grade school math problems) | 94.4% | 92.0% | 96.4% | 96.4% | 95.0% | 95.0% | 91.7% | 94.4% | 92% | 93% | 88.9% | 88.9% | 57.1% | 74.4% | - | - | 79.6% | 62.9% | 81% | - | 81% | - | 
|  | MATH | Challenging math problems (high school algebra, pre-calculus, and others) | 53.2% | 52.9% | 71.1% | 71.1% | 60.1% | 60.1% | 58.5% | 53.2% | 52.9% | 50.4% | 38.9% | 34.1% | 28.4% | - | 76.6% | 70.2% | 30% | 23.9% | 45% | 67.7% | 72.2% | 
| Code | HumanEval | Python code generation | 74.4% | 67.0% | 92.0% | 92.0% | 71.9% | 71.9% | 74.0% | 74.0% | 67% | 81.7% | 79.9% | 75.9% | 40.2% | - | - | - | 62% | 63% | 45.1% | - | - | - | 
|  | Natural2Code | Python code generation. New held out dataset, eval-like, not leaked on the web | 74.9% | 73.9% |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | 

I hope this time it is correct. Please let me know if you have any other requests! 










# Reference
* https://www.confident-ai.com/blog/llm-benchmarks-mmlu-hellaswag-and-beyond





