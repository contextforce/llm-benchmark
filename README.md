# What is LLM Benchmark
# Benchmark Category
There are 8 key LLM Benchmarks across the 4 most critical domains (Language Understanding, Reasoning, Coding, and Conversation). These benchmarks are widely utilized in industry applications and are frequently cited in technical reports. They include:

| Capability | Benchmark | Description |DataSet|
|---|---|---|---|
| General | MMLU | Multiple Choice. Representation of questions in 57 subjects (incl. STEM, humanities, and others) |[DataSet](https://huggingface.co/datasets/lukaemon/mmlu)|
| Reasoning | Big-Bench Hard | Diverse set of challenging tasks requiring multi-step reasoning |[DataSet](https://huggingface.co/datasets/maveriq/bigbenchhard)|
|  | DROP | Reading comprehension (F1 Score) |[DataSet](https://huggingface.co/datasets/ucinlp/drop)|
|  | HellaSwag | Commonsense reasoning for everyday tasks |[DataSet](https://huggingface.co/datasets/Rowan/hellaswag)|
| Math | GSM8K | Basic arithmetic manipulations (incl. Grade School math problems) |[DataSet](https://huggingface.co/datasets/openai/gsm8k)|
|  | MATH | Challenging math problems (incl. algebra, geometry, pre-calculus, and others) |[DataSet](https://github.com/hendrycks/math/)|
| Code | HumanEval | Python code generation |[DataSet](https://paperswithcode.com/dataset/humaneval)|
|  | Natural2Code | Python code generation. New held out dataset HumanEval-like, not leaked on the web |-|

## MMLU
![image](https://github.com/user-attachments/assets/d2e52ce5-fe28-4398-8b13-5df4b79bf930)
<br>

## HellaSwag
![image](https://github.com/user-attachments/assets/9cef8447-b174-42aa-adbc-7b78bb12af9b)
<br>

## MATH
![image](https://github.com/user-attachments/assets/2fb8968c-f672-4562-a514-c09fb140f0a6)
<br>

## DROP
![image](https://github.com/user-attachments/assets/935d9ffc-4b19-4f68-8931-fdcc93c2d517)
<br>

## Chat Arena
![image](https://github.com/user-attachments/assets/251896dc-38d8-49d7-a7e1-d312c89fc578)
<br>

## BBHard
![image](https://github.com/user-attachments/assets/c8e5c863-62d1-4ad0-99e9-af07fa191a68)
<br>

## HumanEval
<img width="749" alt="Screenshot 2024-09-05 at 4 33 36 PM" src="https://github.com/user-attachments/assets/8ceab071-a377-475c-8f72-2c06a2aba768">
<br>

## MT-Bench
![image](https://github.com/user-attachments/assets/ad8480fb-0151-4e33-ac4e-f3a37f15ff65)



<br>
<br>

## LLM Quality Benchmark Leaderboard

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
| Llama 3.1 Instruct - 405B | 88.6% | - | 89% | 61% | 96.8 | 73.8% |
| Llama 3 Instruct - 8B | 68.40% | - | 62% | 61% | 79.60% | 30% |
| Grok 1.5 | 73.00% | - | 63% | - | 62.90% | 23.90% |
| Mistral Large | 81.2% | 89.2% | 45.1% | - | 81% | 45% |
| Gemini 1.5 Flash | 78.90% | 86.5% | 74.3| 85.50% | 86.2 | 54.9% |
| GPT-4T 2024-04-09 | 86.5% | - | - | 87.60% | - | 72.2% | 

<br>
<br>

## LLM Cost Effectiveness Leaderboard

| Model | Provider | Input | Quality | TPS | Context | RPM | TPM | RPD | Input (1M) | output (1M) | cache (1M) |
|---|---|---|---|---|---|---|---|---|---|---|---|
| Gemini 1.5 Flash (Free) | Google | I,V | 84 | 640 | 1M | 15 | 1M | 1500 | - | - | 1M/hr |
| Gemini 1.5 Flash | Google | I,V | 84 | 640 | 1M | 1000 | 4M | - | $0.075 | $0.3 | $0.01875 |
| Gemini 1.5 Pro (Free) | Google | I,V | 95 | 140 | 2M | 2 | 32k | 50 | - | - | - |
| Gemini 1.5 Pro | Google | I,V | 95 | 140 | 2M | 360 | 4M | - | $3.5 | $10.5 | $0.875 |
| Claude 3.5 Sonnet | Anthropic |  | 98 | 90 | 200k |  |  |  | $3 | $15 | $3.75 |
| Claude 3 Haiku | Anthropic |  | 74 | 50 | 200k |  |  |  | $0.25 | $1.25 | $0.3 |
| gpt-4o-2024-08-06 | OpenAI |  | 100 | 125 | 128k |  |  |  | $2.5 | $10 |  |
| gpt-4o-mini | OpenAI |  | 88 | 153 | 128k |  |  |  | $0.15 | $0.6 |  |
| gpt-3.5-turbo-0125 | OpenAI |  | 60 | 116 | 16k |  |  |  | $0.5 | $1.5 |  |
| llama-3.1-405b-chat-fp8 | Meta/Fireworks.ai |  | 100 | 67 | 128k |  |  |  | $3 |  |  |
| llama-3.1-8b-chat-fp8 | Meta/groq |  | 66 | 750 | 128k | 30 | 131072 | 14400 | $0.06 |  |  |
| llama-3.1-70b | Meta/groq |  | 95 | 250 | 128k | 100 | 131072 | 14400 | $0.64 |  |  |


<br>
<br>

## Limitation of LLM Benchmark
* It is more on general capability and not domain specific like legal analysis or medical interpretation.
* It is short in the life span as the LLM has advanced so fast.

<br>
<br>

# Reference
* https://www.confident-ai.com/blog/llm-benchmarks-mmlu-hellaswag-and-beyond
* https://context.ai/compare/gemini-1-5-pro/gemini-flash (Gemini-Flash info)





