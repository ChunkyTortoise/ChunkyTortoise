# Cayman Roden

**AI Engineer | Production LLM Systems, Evaluation, FastAPI, Agent Workflows**

I build and verify production LLM systems, agents, and evaluations for contract AI engineering and client delivery.

[Portfolio](https://chunkytortoise.github.io) · [Reviewer path](https://github.com/ChunkyTortoise/llm-reviewer-path) · [LinkedIn](https://linkedin.com/in/caymanroden) · [DocExtract](https://github.com/ChunkyTortoise/docextract) · [mcp-server-toolkit](https://github.com/ChunkyTortoise/mcp-server-toolkit)

## Start Here (10-minute Verification)

```bash
git clone https://github.com/ChunkyTortoise/llm-reviewer-path
cd llm-reviewer-path
uv sync --group dev
uv run pytest
```

Runs offline without API keys: evaluation gates, approval-token isolation for irreversible actions, and retrieval diagnostics.

## Technical Evidence

| Project | Evidence & Focus | Link |
|---|---|---|
| [llm-reviewer-path](https://github.com/ChunkyTortoise/llm-reviewer-path) | Clone-and-pytest hiring path; offline eval gates & token isolation | Start here |
| [DocExtract](https://github.com/ChunkyTortoise/docextract) | 95.5% weighted field-level accuracy on 28-case offline replay; 200-case corpus; 80% CI gate | Public repository |
| [mcp-server-toolkit](https://github.com/ChunkyTortoise/mcp-server-toolkit) | Python MCP framework with JWT auth, sqlglot read-only AST checks, OpenTelemetry; 600 collected tests | Public repository |
| Acuity Real Estate (private case) | Client-reported 500+ inbound leads; Redis dedup & contact lock; 1,700+ handoff tests; 226 workflow audit | Authorized walkthrough |

## DocExtract replay

Run the committed prediction check without an API key:

```bash
git clone https://github.com/ChunkyTortoise/docextract
cd docextract
python scripts/eval_offline_replay.py --floor 0.85
```

The 95.5% result scores 28 saved predictions; it does not run live extraction. Deployment files include AWS ECS Terraform, Kubernetes manifests and Grafana configuration. See the repository for setup and measurement limits.

## Secondary evidence

[ai-redteam-notes](https://github.com/ChunkyTortoise/ai-redteam-notes) contains public AI safety writeups and reproducible checks.
