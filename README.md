# What is LLM Benchmark

## Models We Love
* **Best for Coding** - Claude Sonnet 3.7 (Oct)
* **Best for Writing** - GPT-4o
* **Best for OCR** - Gemini 1.5 Flash/ Pro
* **Best for Speed Reasoning** - qwq 32B (groq)
* **Best for Cost Saving** - gemini-2.0-flash
* **Best for Latency** - gemini-2.0-flash
<br/>

## Highlights
* **qwq-32B** (reasoining, opens) - This opensource model is from Alibaba that is at the level of deepseek R1 but it is only at 32B parameters (much smaller than DeepSeek R1) - 3/8/2025
* **deepseek R1** (reasoining, open) - This opensource model from China has given a wake-up call to US. It is at the level of o1 but costs way cheaper. Apart from that, it has done few key optimizations that has cut the cost of training substantially. Its launch tanked Nvidia’s stock by $600B, signaling a shift in AI economics and intensifying U.S.-China tech rivalry.
* **grok 3** (close)
* **claude sonnet 3.7** (close) - best in coding
* **openai-o1** (close) 
* **openai-o3-mini** (close) 
* **gemini-2.0-flash** (close) - fast and cheap
* **llama-3.2-90B** (open) - it falls short in reasoning comparing to frontier models but it has vision and 128k context window. Among the free models, it is the best you can find. As of tody, many providers released **llama-3.1-70B** instead. If you are interested, try "**llama-3.1-nemotron-70b-instruct**" from Nivida.

<br/>

## Top LLM Model Comparison

<img width="1370" alt="Screenshot 2025-03-08 at 9 06 31 PM" src="https://github.com/user-attachments/assets/defce740-574a-4521-8e4a-af58a73316d8" />

<img width="1251" alt="Screenshot 2025-03-08 at 9 03 11 PM" src="https://github.com/user-attachments/assets/e66cac92-a4c8-4903-97bf-c2ec8b5c5d6a" />


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
|  | MATH 500| Challenging math problems (incl. algebra, geometry, pre-calculus, and others) |[DataSet](https://github.com/hendrycks/math/)|
|  | AIME-2024| High school math competition  |-|
| Code | HumanEval | Python code generation |[DataSet](https://paperswithcode.com/dataset/humaneval)|
|  | Natural2Code | Python code generation. New held out dataset HumanEval-like, not leaked on the web |-|
|  | LiveCodeBench | LiveCodeBench problems are curated from coding competition platforms: LeetCode, AtCoder, and CodeForces. |[DataSet](https://huggingface.co/livecodebench)|
| Visual Q/A | MMMU | evaluates multimodal models on college-level knowledge and reasoning tasks. It includes 11.5K questions from exams, quizzes, and textbooks across six disciplines: Art & Design, Business, Science, Health & Medicine, Humanities & Social Science, and Tech & Engineering. |[DataSet](https://paperswithcode.com/dataset/humaneval)|


<br/>
<br/>

# Reference
* https://www.confident-ai.com/blog/llm-benchmarks-mmlu-hellaswag-and-beyond
* https://context.ai/compare/gemini-1-5-pro/gemini-flash (Gemini-Flash info)





