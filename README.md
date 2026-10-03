# Cayman Roden

**AI Engineer: I build production LLM systems and the evals and guardrails that make them safe to ship.**

Open to full-time AI Engineer roles, US remote or LA-area hybrid.

- **Ship it** (production LLM apps): [Acuity Real Estate](https://chunkytortoise.github.io/projects.html#acuity), a paid client deployment (Jan–Mar 2026) with Spanish detection and bilingual handoff for client-reported 500+ inbound leads, and [DocExtract](https://github.com/ChunkyTortoise/docextract).
- **Measure it** (evals as CI): the [DocExtract](https://github.com/ChunkyTortoise/docextract) eval gate and [llm-reviewer-path](https://github.com/ChunkyTortoise/llm-reviewer-path).
- **Secure it** (agent and MCP security): [ai-redteam-notes](https://github.com/ChunkyTortoise/ai-redteam-notes) and [mcp-server-toolkit](https://github.com/ChunkyTortoise/mcp-server-toolkit).

## Featured projects

<table>
<tr>
<td width="50%" valign="top"><a href="https://github.com/ChunkyTortoise/docextract"><b>DocExtract</b></a><br>Two-pass Claude extraction with pgvector search; 95.5% weighted field-level score on a 28-fixture offline replay, with a CI check that fails below 0.85.<br><sub>FastAPI · Claude API · PostgreSQL/pgvector · Redis + ARQ · OpenTelemetry</sub></td>
<td width="50%" valign="top"><a href="https://github.com/ChunkyTortoise/ai-redteam-notes"><b>ai-redteam-notes</b></a><br>Pre-registered prompt-injection research on agent tool dispatch, plus a zero-dependency substrate auditor that runs in CI.<br><sub>Python · MCP harnesses · open-weight Llama 3.3 70B · offline repro</sub></td>
</tr>
<tr>
<td width="50%" valign="top"><a href="https://github.com/ChunkyTortoise/mcp-server-toolkit"><b>mcp-server-toolkit</b></a><br>MCP server library with JWT/JWKS auth, sqlglot read-only SQL checks, caching and OpenTelemetry spans; 627 tests.<br><sub>Python · MCP SDK · pydantic · sqlglot · PyJWT · OpenTelemetry</sub></td>
<td width="50%" valign="top"><a href="https://github.com/ChunkyTortoise/llm-reviewer-path"><b>llm-reviewer-path</b></a><br>Offline eval gate, approval tokens for irreversible agent actions, and duplicate-retry suppression; 36 tests, no API keys.<br><sub>Python · pytest · uv · GitHub Actions</sub></td>
</tr>
</table>

## Try in 60 seconds

```bash
git clone https://github.com/ChunkyTortoise/docextract && cd docextract && python scripts/eval_offline_replay.py --floor 0.85
```

Replays 28 committed extraction fixtures against the CI floor. Python 3.10+, no API key.

**Stack:** Python · FastAPI · Claude (Anthropic API) · PostgreSQL + pgvector · Redis + ARQ · MCP · OpenTelemetry · pytest · GitHub Actions eval gates · Docker

## Contact

[Portfolio](https://chunkytortoise.github.io) · [LinkedIn](https://linkedin.com/in/caymanroden) · [Email](mailto:caymanroden@gmail.com)
