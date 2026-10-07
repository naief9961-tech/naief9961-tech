# NAIF Gravity

Developer-focused diagnostics and bounded repair for **AI agents, MCP, APIs, authentication, webhooks and automation**.

**Live:** https://naifgravity.com/?utm_source=github&utm_medium=profile&utm_campaign=github_funnel

## What NAIF Gravity solves

- **MCP diagnostics & repair** — initialize failures, `tools/list`, schema mismatches, transport/session problems.
- **API & Auth troubleshooting** — HTTP 401/403, OAuth `invalid_grant`, permissions, token/config mismatches.
- **Webhook recovery** — signature verification, payload parsing, delivery/handler gaps, retries and idempotency.
- **Agent integration debugging** — tool-call failures, endpoint contracts, bounded automation repair.

The operating model is intentionally narrow: collect reproducible evidence, identify the smallest repair, verify the result, and avoid unnecessary rebuilds.

## Free GitHub diagnostics

A public developer-facing diagnostic hub is available in:

**[ai-growth-engine → NAIF Gravity Diagnostic Hub](https://github.com/naief9961-tech/ai-growth-engine/blob/main/NAIF-GRAVITY.md)**

It includes:
- a local read-only MCP health-check script,
- searchable troubleshooting guides,
- structured issue templates for MCP, API/Auth and webhook failures,
- security guidance that explicitly excludes secrets and private keys.

## For AI agents

NAIF Gravity exposes machine-readable discovery and agent-facing paths from the production domain. Start at:

https://naifgravity.com/

The public GitHub repositories provide evidence, examples and reproducible diagnostics. Commercial checkout and delivery stay on NAIF Gravity.

## Current engineering work

- AI-agent and MCP interoperability.
- API/Auth/Webhook troubleshooting.
- Reproducible diagnostics and validation.
- Public technical contributions, issue triage and integration testing.

## Security

Do **not** publish API keys, bearer tokens, cookies, private keys, seed phrases, payment credentials or customer data in GitHub issues.

Use only endpoints and systems you own or are authorized to test.
