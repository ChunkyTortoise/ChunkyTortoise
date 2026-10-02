# Cayman Roden

**AI Engineer · production LLM systems, agents, and evals · Python and FastAPI**

I build the application layer around LLMs: retrieval, tool use, structured outputs, evaluation gates, and a human handoff for when the model should stop. Contract-first, with three paid AI contracts behind the public code below.

[Portfolio](https://chunkytortoise.github.io) · [Resume (PDF)](https://chunkytortoise.github.io/resume/cayman-roden-ai-engineer.pdf) · [LinkedIn](https://linkedin.com/in/caymanroden) · [Email](mailto:caymanroden@gmail.com)

**Open to:** AI Engineer / Applied AI Engineer, AI Backend / LLM Platform Engineer, and selective Forward Deployed Engineer roles. US-based, remote or LA-area hybrid. Contract-first, and open to full-time roles on this stack.

## Hero repositories

| Repository | What it does |
|---|---|
| [**DocExtract**](https://github.com/ChunkyTortoise/docextract) | Classifies PDFs and images (invoices, receipts, purchase orders, bank statements, medical records, ID documents) and extracts structured fields with a two-pass Claude pipeline. 95.5% weighted field-level accuracy on a 28-case offline replay you can rerun without an API key, plus an 80% test-coverage gate in CI. |
| [**mcp-server-toolkit**](https://github.com/ChunkyTortoise/mcp-server-toolkit) | FastMCP extensions for authentication, read-only SQL validation, and OpenTelemetry tracing. 600 collected tests, Python 3.10 to 3.14. |
| [**ai-redteam-notes**](https://github.com/ChunkyTortoise/ai-redteam-notes) | Public AI safety writeups with reproducible checks. |

Want a quick check? [llm-reviewer-path](https://github.com/ChunkyTortoise/llm-reviewer-path) is a 10-minute clone-and-`pytest` check that runs offline with no API key.

## Paid delivery

- **Acuity Real Estate** (Jan to Mar 2026): SMS lead qualification with Spanish detection and bilingual human handoff for a client-reported 500+ inbound leads. FastAPI, Redis, and GoHighLevel as the system of record. 1,700+ tests at handoff and an audit of 226 existing CRM workflows. [Project scope summary](https://github.com/ChunkyTortoise/llm-reviewer-path/blob/main/receipts/fde_scope/ACUITY.md); the code is private and available in a walkthrough.
- **DocExtract**: built under a paid client engagement, and the code and its offline eval are public in the repo above.
- **EnterpriseHub** (2025 to 2026): built the orchestration layer for a real estate AI platform with three specialized chatbots, including cross-bot handoffs with loop prevention and rate limiting. The client repo is private; walkthrough on request.

## Stack

- **Backend:** Python, FastAPI, PostgreSQL, Redis, Docker, GitHub Actions
- **LLM and retrieval:** Claude, OpenAI, and Gemini APIs, RAG, pgvector, BM25 with reciprocal rank fusion, tool use, structured output, MCP
- **Evaluation and reliability:** pytest, RAGAS, LLM-as-judge, adversarial fixtures, OpenTelemetry, structured logging

## Writing

- [Blog](https://chunkytortoise.github.io/blog.html): testing LLM systems, multi-agent orchestration, and contract testing with pact-python v3.

Before engineering, I spent 10 years in client-facing operations, which is why I scope tightly, write down what "done" means, and build the handoff path first.
