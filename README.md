# How-LLMs-Work

## 1. Data Preprocessing and Tokenizing
Code idea: Tokenize and prep a large corpus of text

Resources: 
- [Huggingface](https://huggingface.co/learn/llm-course/en/chapter2/4)
- [Coursera](https://www.coursera.org/learn/classification-vector-spaces-in-nlp)

## 2. Transformers
What does the architecture look like?

Code idea: Write a transformer from scratch

Resources:
- [DeepLearning.AI](https://www.deeplearning.ai/short-courses/how-transformer-llms-work/)
- [Jay Alammar](https://jalammar.github.io/illustrated-transformer/)
- [Attention Is All You Need (classic)](https://arxiv.org/abs/1706.03762)


## 3. Training Transformers
Parallelization and running hella GPUs

Code idea: Train on a smaller amount of data

Resources:
- [HuggingFace](https://huggingface.co/learn/llm-course/chapter1/3?fw=pt)
- [Andrej](https://youtu.be/zjkBMFhNj_g?si=qpSRvibx9nmFojF7)
- [Andrej again](https://youtu.be/kCc8FmEb1nY?si=ziXytqmCcvIeQRVs)
- [OpenAI](https://arxiv.org/abs/2001.08361)

## 4. Alignment
GPT-3 --> ChatGPT
- SFT
- RLHF or GRPO reward functions

Code idea: RLHF, or LLM as a judge to get better outputs. Could try turning next-word-prediction into a question-answer machine (chat)

Resources:
- [OpenAI](https://openai.com/index/instruction-following/)
- [Anthropic](https://www.anthropic.com/research/constitutional-ai-harmlessness-from-ai-feedback)

## 5. Applications
- Prompt Engineering
- Zero-shot, few-shot, CoT
- RAG

Code idea: Implement a reasoning model, with more RAG context

Resources:
- [DeepLearning.AI](https://www.deeplearning.ai/short-courses/chatgpt-prompt-engineering-for-developers/)
- [CoT](https://arxiv.org/abs/2201.11903)
- 

## 6. Serving an LLM in prod
- model distallation if needed
- token streaming
- API latency

Code idea: Ship a model to a website

Resources:
- [DeepLearning.AI](https://www.deeplearning.ai/short-courses/llmops/)