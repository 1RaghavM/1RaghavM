# Raghav Mehta

I ship AI applications and developer tools end to end: an MCP server that lets coding agents generate images and video, a 345-lesson C++ learning platform with sandboxed grading and an AI tutor, an agent-backed FastAPI backend, and computer-vision models I train and quantize on my own GPU.

**Open to 2027 AI/ML and software engineering internships.** I'm especially interested in AI applications, developer tools, and backend work.

## Featured projects

**[visualgen-mcp](https://github.com/1RaghavM/visualgen-mcp)** · Python · Model Context Protocol (MCP)
An MCP server that lets Claude Code generate images (Imagen 4) and 8-second videos (Veo 3.1) through the Gemini API and writes the files straight into the project. It exposes six stdio tools, including async video jobs (submit, then poll), plus a setup wizard and a Claude Code skill that asks before expensive runs. CI runs ruff, mypy, and pytest on Python 3.11 and 3.12.

**[cpproad](https://github.com/1RaghavM/cpp-course)** · TypeScript · Next.js · Supabase
An interactive C++ course covering all 34 chapters and 345 lessons of learncpp.com. Code runs in a Judge0 sandbox and is graded against per-exercise test cases. A bring-your-own-key Gemini tutor stores keys encrypted with AES-256-GCM and gives hints in four escalating tiers, so it can't open with the answer. It also has spaced-repetition review, optional GitHub sync of passed solutions, and a Vitest test suite.

**[dormdish-backend](https://github.com/1RaghavM/dormdish-backend)** · Python · FastAPI
The backend for DormDish, a college dining and nutrition app: campus menus, meal plans, food-photo analysis with Gemini, food logging, and subscriptions. Its "Ask DormDish" conversational agent streams versioned server-sent events, persists runs so they can be recovered, requires explicit confirmation before saving a meal, and is rolled out behind feature flags and a kill switch.

**[FireDetection](https://github.com/1RaghavM/FireDetection)** · Python · YOLO11
A YOLO11n model fine-tuned to detect flames and smoke. It reached validation mAP50 0.945 (mAP50-95 0.651) after 100 epochs. The INT8 OpenVINO export is 3.2 MB and keeps mAP50-95 at 0.637 at 13.6 ms per image.

**[ai-engineering-illustrated-diagrams](https://github.com/1RaghavM/ai-engineering-illustrated-diagrams)**
Illustrated explanations of how AI systems work: code sandboxes, MCP, LLM inference serving, computer-use agents, and agent harnesses. Written for my [Substack](https://ragmehta.substack.com).

## Also building

- [ebay-agent](https://github.com/1RaghavM/ebay-agent): send a few photos and a sentence on WhatsApp and get an eBay sandbox listing back. It's built on a custom 4-tool eBay MCP server whose test suite requires at least 75% coverage overall and 100% on the eBay client.
- [arbiter](https://github.com/1RaghavM/arbiter): routes chat requests across OpenAI, Anthropic, and Google models and compares cost, latency, and quality against fixed-model baselines (React, FastAPI, PostgreSQL).
- [network-rag-api](https://github.com/1RaghavM/network-rag-api): a minimal retrieval-augmented generation (RAG) API using FastAPI, Chroma, and a local Ollama model.
- [vision-tune](https://github.com/1RaghavM/vision-tune): a vision-language model fine-tuned on an RTX 3090 to summarize X-ray images.
- [l1-cache](https://github.com/1RaghavM/l1-cache): a C++17 memory-latency experiment, with a written analysis of why the naive approach measures cache misses rather than L1 hits.

## Stack

Python · TypeScript · C++ · PyTorch · Ultralytics · FastAPI · Next.js · Supabase · PostgreSQL · Docker

## Get in touch

If you're hiring for 2027 AI/ML or SWE internships, I'd like to hear from you. Read my writing on [Substack](https://ragmehta.substack.com), browse my code on [GitHub](https://github.com/1RaghavM), or open an issue on any of the repos above.
