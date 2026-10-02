# Cayman Roden

**AI Engineer · production LLM systems, agents, and evals · Python and FastAPI**

I build the application layer around LLMs: retrieval, tool use, structured outputs, evaluation gates, and a human handoff for when the model should stop. Contract-first, with three paid AI contracts behind the public code below.

[Portfolio](https://chunkytortoise.github.io) · [Resume (PDF)](https://chunkytortoise.github.io/resume/cayman-roden-ai-engineer.pdf) · [LinkedIn](https://linkedin.com/in/caymanroden) · [Email](mailto:caymanroden@gmail.com)

**Open to:** AI Engineer / Applied AI Engineer, AI Backend / LLM Platform Engineer, and selective Forward Deployed Engineer roles. US-based, remote or LA-area hybrid. Contract-first, and open to full-time roles on this stack.

## Start here: a 10-minute check

```bash
git clone https://github.com/ChunkyTortoise/llm-reviewer-path
cd llm-reviewer-path
uv sync --group dev
uv run pytest
```

Runs offline with no API key: evaluation gates, approval-token isolation for irreversible actions, and retrieval diagnostics.

## Hero repositories

| Repository | What it proves |
|---|---|
| [**llm-reviewer-path**](https://github.com/ChunkyTortoise/llm-reviewer-path) | Clone-and-pytest review path for eval gates, action boundaries, retrieval failures, and scoping receipts. No API key needed. |
| [**DocExtract**](https://github.com/ChunkyTortoise/docextract) | Document extraction with eval-gated CI. 95.5% weighted field-level accuracy, measured on a 28-case offline replay only. Separate 200-case authoring corpus and an 80% test-coverage gate in CI. |
| [**mcp-server-toolkit**](https://github.com/ChunkyTortoise/mcp-server-toolkit) | FastMCP extensions for authentication, read-only SQL validation, and OpenTelemetry tracing. 600 collected tests, Python 3.10 to 3.14. |

The DocExtract number scores 28 saved predictions; it does not run live extraction. Reproduce it with `python scripts/eval_offline_replay.py --floor 0.85`, which fails if accuracy drops below 85% (a separate check from the 80% coverage gate).

## Paid delivery

- **Acuity Real Estate** (Jan to Mar 2026): SMS lead qualification with Spanish detection and bilingual human handoff for a client-reported 500+ inbound leads. FastAPI, Redis, and GoHighLevel as the system of record. 1,700+ tests at handoff and an audit of 226 existing CRM workflows. [Public scope receipt](https://github.com/ChunkyTortoise/llm-reviewer-path/blob/main/receipts/fde_scope/ACUITY.md); private code by walkthrough.
- **DocExtract**: paid work with the public offline eval above.
- **EnterpriseHub** (2025 to 2026): confidential AI application work. Walkthrough on request.

## Stack

**Backend:** Python, FastAPI, PostgreSQL, Redis, Docker, GitHub Actions
**LLM and retrieval:** Claude, OpenAI, and Gemini APIs, RAG, pgvector, BM25 with reciprocal rank fusion, tool use, structured output, MCP
**Evaluation and reliability:** pytest, RAGAS, LLM-as-judge, adversarial fixtures, OpenTelemetry, structured logging

## Also on GitHub

- [ai-redteam-notes](https://github.com/ChunkyTortoise/ai-redteam-notes): public AI safety writeups with reproducible checks.
- [Writing](https://chunkytortoise.github.io/blog.html): testing LLM systems, multi-agent orchestration, and contract testing with pact-python v3.

Before engineering, I spent 10 years in client-facing operations, which is why I scope tightly, write down what "done" means, and build the handoff path first.
