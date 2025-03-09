# What is LLM Benchmark

## Models We Love
* **Best for Coding** - Claude Sonnet 3.5 (Oct)
* **Best for Writing** - GPT-4o
* **Best for OCR** - Gemini 1.5 Flash/ Pro
* **Best for Speed Reasoning** -
* **Best for Cost Saving** -
<br/>

## Benchmarks
* **GPQA** (Graduate-Level Google-Proof Q&A)
* **AIME** (American Invitational Mathematics Examination)
* **MATH-500**
* **LiveCodeBench**

<br/>

## Highlights
* **qwq-32B** - This opensource model is from Alibaba that is at the level of deepseek R1 but it is only at 32B parameters (much smaller than DeepSeek R1) - 3/8/2025
* **deepseek R1** - This opensource model from China has given a wake-up call to US. It is at the level of o1 but costs way cheaper. Apart from that, it has done few key optimization that has cut the cost of training substantially.
* **llama-3.2-90B** model falls short in reasoning comparing to frontier models but it has vision and 128k context window. Among the free models, it is the best you can find. As of tody, many providers released **llama-3.1-70B** instead. If you are interested, try "**llama-3.1-nemotron-70b-instruct**" from Nivida.
* **llama-3.1-8B-Instant-128k** from Groq can produce 750 token/sec at **I:$0.05/1M, O:$0.08/M** tokens. It is great for speed reasoning.
* **gemini-1.5-flash** is a surprise to the market. It has good quality, 1M context window size, fast and cost-effective. Paid version allows you to reach 2k requests/minute with 4M TPM. That is way above all models in the market in terms of speed and context size. - **I:$0.075/1M, O:$0.3/M**

<br/>

## Top LLM Model Comparison
<img width="1342" alt="Screenshot 2024-10-27 at 9 49 11 PM" src="https://github.com/user-attachments/assets/ba73d1cf-1c17-4a97-97dd-360ccf827794">

<img width="903" alt="Screenshot 2024-10-27 at 9 50 03 PM" src="https://github.com/user-attachments/assets/a56be7e2-b221-40b1-8a99-545b3a85fb58">

<img width="859" alt="Screenshot 2024-10-27 at 9 50 34 PM" src="https://github.com/user-attachments/assets/c6328bf9-9d0f-4018-b263-b8a2895506a7">

## State of Art (updated 10/27/2024)
<img width="1072" alt="Screenshot 2024-10-27 at 5 23 12 PM" src="https://github.com/user-attachments/assets/15a636e7-f17d-4675-9103-c0d92fe4ca2f">

## Benchmark Category
There are 8 key LLM Benchmarks across the 4 most critical domains (Language Understanding, Reasoning, Coding, and Conversation). These benchmarks are widely utilized in industry applications and are frequently cited in technical reports. They include:

| Capability | Benchmark | Description |DataSet|
|---|---|---|---|
| Reasoning | GPQA | Gradudate level reasoning |[DataSet]()|
|  | Big-Bench Hard | Diverse set of challenging tasks requiring multi-step reasoning |[DataSet](https://huggingface.co/datasets/maveriq/bigbenchhard)|
|  | DROP | Reading comprehension (F1 Score) |[DataSet](https://huggingface.co/datasets/ucinlp/drop)|
|  | HellaSwag | Commonsense reasoning for everyday tasks |[DataSet](https://huggingface.co/datasets/Rowan/hellaswag)|
| General | MMLU | Multiple Choice. Representation of questions in 57 subjects (incl. STEM, humanities, and others) |[DataSet](https://huggingface.co/datasets/lukaemon/mmlu)|
|  | MMLU Pro | TBA |[DataSet]
| Math | GSM8K | Basic arithmetic manipulations (incl. Grade School math problems) |[DataSet](https://huggingface.co/datasets/openai/gsm8k)|
|  | MATH | Challenging math problems (incl. algebra, geometry, pre-calculus, and others) |[DataSet](https://github.com/hendrycks/math/)|
|  | AIME-2024| High school math competition  |-|
| Code | HumanEval | Python code generation |[DataSet](https://paperswithcode.com/dataset/humaneval)|
|  | Natural2Code | Python code generation. New held out dataset HumanEval-like, not leaked on the web |-|
| Visual Q/A | MMMU | Python code generation |[DataSet](https://paperswithcode.com/dataset/humaneval)|


<br/>
<br/>

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





