![OpenZoo.ai](logo.png)

---

The OpenZoo API is the easiest way to use open-source LLMs because:

1. **You already know how to use it**: simply use the official [OpenAI](https://github.com/openai) client for your language of choice by changing the base_url parameter
2. **You don't need to select a model from the ever-changing leaderboards** - just provide a **spec** like 'chat', 'summarization', 'code' or 'math', we always serve the latest best model for the job
3. **We keep adding features so you can write less code**: If you specify 'chat safe' (releasing next Friday!), we add a [Llama-guard](https://ai.meta.com/research/publications/llama-guard-llm-based-input-output-safeguard-for-human-ai-conversations/) circuit-breaker to keep your responses safe! Soon, you will be able to just specify 'chat safe eu-compliant spanish' and save precious lines of code that you will need to maintain.
4. **When you need to, you can still specify exactly which model you want**: simply specify the HuggingFace handle like 'mistralai/Mixtral-8x7B-Instruct-v0.1' and all parameters supported by the Openai client to get full control when you need it.

*We are in closed alpha right now, watch this space!*

---
