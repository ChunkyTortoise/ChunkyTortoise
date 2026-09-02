# Cayman Roden

**AI Engineer | Python, FastAPI, LLM applications, agents, and evaluation**

I build LLM applications, agents, and evals for contract AI engineering. The named paid engagement is Acuity Real Estate. Other public repos below are independent portfolio work unless a line says paid.

[Portfolio](https://chunkytortoise.github.io) · [LinkedIn](https://linkedin.com/in/caymanroden) · [Acuity SMS bots](https://github.com/ChunkyTortoise/jorge_real_estate_bots) · [DocExtract](https://github.com/ChunkyTortoise/docextract)

## Interview proofs

| Project | Evidence | Context |
|---|---|---|
| [Acuity SMS bots](https://github.com/ChunkyTortoise/jorge_real_estate_bots) | Client-reported 500+ inbound leads during a January to March 2026 deployment; 1,700+ tests at handoff; audit of 226 existing GHL workflows | Paid engagement |
| [DocExtract](https://github.com/ChunkyTortoise/docextract) | 95.5% weighted field-level accuracy on 28 committed offline replay fixtures; separate 202-case authoring corpus; 80% CI coverage gate | Independent engineering |

## Cloneable reviewer index

The two hero repositories above hold the primary evidence. This small index makes their release-gate, action-boundary, retrieval-failure, and client-scoping patterns runnable without an API key:

```bash
git clone https://github.com/ChunkyTortoise/llm-reviewer-path
cd llm-reviewer-path
uv sync --group dev
uv run pytest
```

## Independent portfolio systems

- [chatbot-widget](https://github.com/ChunkyTortoise/chatbot-widget) - multi-tenant chat widget (historical learning project — see its banner; current work starts at [llm-reviewer-path](https://github.com/ChunkyTortoise/llm-reviewer-path))
- [ai-workflow-api](https://github.com/ChunkyTortoise/ai-workflow-api) - YAML-driven workflow API

## Engineering notes

- [Eval-driven multi-model runs](https://chunkytortoise.github.io/case-studies/eval-driven-multi-model-runs.html): personal developer infrastructure for one-writer / independent-gate coordination. Not a product.

## Role fit

Strongest: AI Engineer, Applied AI Engineer, AI Backend Engineer, selective Forward Deployed Engineer.

Not targeting: Senior/Staff/Principal/Lead titles, research-scientist roles, model-training-heavy ML roles, QA-only roles.
