# HeyNina101/generative_ai_project

* [HeyNina101/generative_ai_project](https://github.com/HeyNina101/generative_ai_project)

```
📁 config/ → YAML config for models, prompts, logging
📁 data/ → Prompts, embeddings, and other dynamic content
📁 examples/ → Minimal scripts to test key features
📁 notebooks/ → Quick experiments and prototyping
📁 tests/ → Unit, integration, and end-to-end tests

📁 src/ → The core engine — all logic lives here:
├── agents/ → Agent classes: planner, executor, base agent
├── memory/ → Short-term and long-term memory modules
├── pipelines/ → Chat flows, doc processing, and task routing
├── retrieval/ → Vector search and document lookup
├── skills/ → Extra abilities: web search, code execution
├── vision_audio/ → Multimodal processing: image and audio
├── prompt_engineering/→ Prompt chaining, templates, few-shot logic
├── llm/ → OpenAI, Anthropic, and custom LLM routing
├── fallback/ → Recovery logic when LLMs fail
├── guardrails/ → PII filters, output validation, safety checks
├── handlers/ → Input/output processing and error management
└── utils/ → Logging, caching, rate limiting, token counting
```
