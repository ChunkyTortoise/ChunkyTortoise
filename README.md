# Cayman Roden

**AI Engineer | Python, FastAPI, LLM applications, agents, and evaluation**

I build LLM applications, agents, and evals for contract AI engineering. Named paid engagements include DocExtract and Acuity Real Estate. Start with the public technical evidence below; Acuity is a private client case.

[llm-reviewer-path](https://github.com/ChunkyTortoise/llm-reviewer-path) · [DocExtract](https://github.com/ChunkyTortoise/docextract) · [mcp-server-toolkit](https://github.com/ChunkyTortoise/mcp-server-toolkit) · [Portfolio](https://chunkytortoise.github.io) · [LinkedIn](https://linkedin.com/in/caymanroden)

## Interview proofs

| Project | Evidence | Context |
|---|---|---|
| [llm-reviewer-path](https://github.com/ChunkyTortoise/llm-reviewer-path) | Offline evidence index with fixed evaluation, retrieval, action-boundary and delivery-scoping examples; clone and run pytest without an API key | Public source; examples do not establish production controls |
| [DocExtract](https://github.com/ChunkyTortoise/docextract) | 95.5% weighted field-level accuracy on 28 saved-prediction offline replay cases; separate authoring corpus of 200 cases plus two metadata rows | Paid contract; public source; replay is not a live-model or held-out result |
| [mcp-server-toolkit](https://github.com/ChunkyTortoise/mcp-server-toolkit) | Python MCP framework with opt-in auth and telemetry components | Public source; follow the repository's source-install instructions |
| Acuity Real Estate SMS qualification (private case) | Client-reported 500+ inbound leads during January to March 2026; historical handoff inventory of 1,700+ tests; saved inventory of 226 CRM workflow entries with conflict candidates, not full manual validation | Private archive; authorized walkthrough only |

## Run the offline reviewer index

The public `llm-reviewer-path` repository has fixed examples of evaluation, an in-memory action boundary, retrieval failures and delivery scoping. Its tests run without an API key after dependency installation; the examples do not establish human approval isolation, a complete five-case gate, branch protection or production CRM behavior:

```bash
git clone https://github.com/ChunkyTortoise/llm-reviewer-path
cd llm-reviewer-path
uv sync --group dev
uv run pytest
```

## Other portfolio systems

- [chatbot-widget](https://github.com/ChunkyTortoise/chatbot-widget) - multi-tenant chat widget (historical learning project; current technical proof starts at [llm-reviewer-path](https://github.com/ChunkyTortoise/llm-reviewer-path))
- [ai-workflow-api](https://github.com/ChunkyTortoise/ai-workflow-api) - YAML-driven workflow API

## Engineering notes

- [Eval-driven multi-model runs](https://chunkytortoise.github.io/case-studies/eval-driven-multi-model-runs.html): personal developer infrastructure for one-writer / independent-gate coordination. Not a product.

## Role fit

Strongest: AI Engineer, Applied AI Engineer, AI Backend Engineer, selective Forward Deployed Engineer.

Not targeting: Senior/Staff/Principal/Lead titles, research-scientist roles, model-training-heavy ML roles, QA-only roles.
