# Rayhan Patel

Software engineer building AI agents: production agents, agent memory and LLM evaluation.

M.S. Applied Machine Learning, University of Maryland (May 2027). Open to full-time roles from June 2027, San Francisco Bay Area or relocating.

### Experience

**[3E](https://www.3eco.com)** · AI Engineer Intern, AI Platform · Jun to Aug 2026\
Built the core of a multi-tenant agent-memory MCP service on AWS Lambda and DynamoDB (six operations, deny-by-default tenant access, versioned writes) and its deterministic spec-conformance harness. Found and fixed a warm-container credential leak; the fix landed on main. Benchmarked Hindsight, Cognee and Zep/Graphiti on LoCoMo and LongMemEval, and calibrated an LLM judge against blinded human graders: the rubric, not the judge model, was the accuracy lever.

**[Euler AI](https://eulerai.app)** · Founding ML/Software Engineer · Mar to Jul 2025\
Built a conversational shopping agent on FastAPI (intent routing, a reranker, PII guardrails) and a G-Eval pipeline that measured hallucination across the product.

### Research

**[EvoRank: LLM-Guided Evolution of Multi-Objective Learning-to-Rank Pipelines](https://arxiv.org/abs/2609.22196)** · [code](https://github.com/shabazpatel/evorank)\
First author, equal contribution · GenAIECommerce'26 workshop at RecSys 2026\
An LLM evolves complete ranking pipelines, gated by a pre-spend headroom check, and its winners are judged on 59,902 held-out queries. All three runs beat an Optuna-tuned LambdaMART on relevance (best +0.0057 NDCG@10, p < 0.0001), and a one-shot late submission would have placed 20th of 340 on the original Kaggle test set.

**[Building Domain-Specific LLMs Faithful to the Islamic Worldview](https://arxiv.org/abs/2312.06652)**\
Co-author · Muslims in ML workshop at NeurIPS 2023\
Built the evaluation (BERTScore, embedding similarity) comparing prompting, RAG and GPT-3.5 fine-tuning, and presented the paper.

### Selected projects

**[AI Resume Agent](https://github.com/Rayhanpatel/AI-Resume-Agent)** · [live](https://chat.rayhanpatel.com)\
Production AI agent on Gemini and FastAPI: 10 backend modules with graceful degradation, and five LLM-as-judge evaluators in Langfuse scoring every answer.

**[HVAC Copilot](https://github.com/Rayhanpatel/Ycombinator-Cactus-Deepmind)** · YC × Cactus × Google DeepMind hackathon, 4-person team\
Built the on-device agent runtime on Gemma 4 E4B: a six-tool function-calling surface with the on-device/online boundary enforced in the dispatcher, and a streaming parser for Gemma 4's tool-call formats. Profiled time to first token at 217 ms bare-model vs 3.9 to 4.5 s with ~935 tokens of system prompt and tool schemas, and traced it to CPU prefill.

**[FunctionGemma Router](https://github.com/Rayhanpatel/functiongemma-hackathon)** · 2nd place, Cactus × Google DeepMind hackathon · built all of it (three-person registration)\
Hybrid on-device and cloud function calling (FunctionGemma-270M with Gemini 2.5 Flash Lite): 0.99 F1 at 548 ms average latency.

**Top-K k-NN kernel for the Cerebras WSE-2** · CSL, take-home, code on request\
Passes all 6 grader cases with 2.68× fewer cycles than the first correct version; a radix-sort variant was measured and rejected at +24%.

**[PathGuard](https://github.com/Rayhanpatel/PathGuard)** · UMD × Ironsite hackathon, team lead\
Architected the dual-pipeline system and built its on-device VLM narrator (Liquid LFM 2.5 via Cactus), whose scene-specific prompts drive the team's real-time hazard detection (Grounding DINO, SAM2, Depth Anything V2).

Open-source contributor to [Mem0](https://github.com/mem0ai/mem0).

---

[chat.rayhanpatel.com](https://chat.rayhanpatel.com) · [LinkedIn](https://www.linkedin.com/in/rayhan-patel-cs) · rayhanbp@umd.edu
