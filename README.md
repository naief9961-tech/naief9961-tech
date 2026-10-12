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

NAIF Gravity exposes machine-readable discovery and agent-facing paths from the production domain:

- [Agent Card](https://naifgravity.com/.well-known/agent-card.json) — identity, skills and advertised interfaces.
- [Remote MCP endpoint](https://naifgravity.com/mcp) — Streamable HTTP; use an MCP client rather than a normal browser GET.
- [Agent service catalog](https://naifgravity.com/api/agent/catalog) — consult current descriptions, eligibility and purchase instructions.
- [Individual services](https://naifgravity.com/services?utm_source=github&utm_medium=profile&utm_campaign=one_time_services) — current one-time service catalog; new monthly subscriptions are paused.

Discovery metadata does not prove successful payment or authorize a production repair.

The public GitHub repositories provide evidence, examples and reproducible diagnostics. Commercial checkout and delivery stay on NAIF Gravity.


## October 2026 launch prices — automatic, no coupon

**14 bounded technical services have a time-limited launch discount**, applied to new quotes only until **October 26, 2026 at 05:40 UTC or the first 10 verified purchases of eligible launch products**, whichever comes first. For example: NAIF API Fixer **$89 → $79**, Data Factory **$129 → $115**, Automation Factory **$199 → $179**, AI Agent Engineering Sprint **$249 → $219**. Browse the [full current offer table](https://github.com/naief9961-tech/ai-growth-engine#launch-offer--one-time-technical-services-october-1226-2026). An agent uses the **[live service catalog](https://naifgravity.com/api/agent/catalog)** and accepted quote as its authoritative current price; it does not need a coupon, and existing quotes are not repriced.

**Machine-paid instant x402 APIs** are separately discoverable via the [x402 resource manifest](https://naifgravity.com/.well-known/x402) and [OpenAPI](https://naifgravity.com/openapi.json). Four current full-scope products cost **$1/$2/$3/$5 USDC per call on Base**; proposed lower-price Lite tools are **not live yet**. Engineering and repair services may accept agent-initiated checkout but typically require a verified paid Work handoff before delivery. Never infer successful payment from a 402 challenge or a listing.

## Purchase a bounded JSON check

[Buy JSON Validity Check](https://naifgravity.com/service/json-validity-check) or use [x402scan → Try with AgentCash](https://www.x402scan.com/server/a95c7242-15af-44a7-a85d-2b2ffa251755). The paid x402 v2 API costs **1 USDC on Base mainnet** per bounded check; [OpenAPI](https://naifgravity.com/openapi.json) publishes its request and payment metadata. See the [purchase instructions](https://github.com/naief9961-tech/ai-growth-engine#buy-the-json-check-with-usdc-on-base) for the 4096-byte limit and payment flow.

VPN/proxy use is no longer a standalone blocker. Regional eligibility remains: Saudi-classified connections receive Apple Pay, while eligible international connections can use Base USDC. Follow the live checkout; GitHub itself does not process the purchase. Other services have their own prices and delivery scopes.

## Current engineering work

- AI-agent and MCP interoperability.
- API/Auth/Webhook troubleshooting.
- Reproducible diagnostics and validation.
- Public technical contributions, issue triage and integration testing.

## Security

Do **not** publish API keys, bearer tokens, cookies, private keys, seed phrases, payment credentials or customer data in GitHub issues.

Use only endpoints and systems you own or are authorized to test.
