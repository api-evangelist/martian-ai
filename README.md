# Martian

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Martian operates an LLM model router and gateway that dynamically routes each request to the best underlying model across providers for the optimal balance of quality, latency, and cost. The Martian Gateway exposes a drop-in, OpenAI-compatible REST API (and an Anthropic Messages-compatible surface) so applications can route across a large catalog of models by changing only the base URL.

**Areas:** Artificial Intelligence · LLM · Model Router · Gateways · Cost Optimization

## Martian on APIs.io

Everything profiled for Martian is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/martian-ai/](https://apis.io/providers/martian-ai/)** — or go straight to one of the APIs or properties below.

### APIs (3)

- [Martian Chat Completions API](https://apis.io/apis/martian-ai/martian-ai-chat-completions-api/) — The Chat Completions API from Martian — 1 operation(s) for chat completions.
- [Martian Messages API](https://apis.io/apis/martian-ai/martian-ai-messages-api/) — The Messages API from Martian — 1 operation(s) for messages.
- [Martian Models API](https://apis.io/apis/martian-ai/martian-ai-models-api/) — The Models API from Martian — 1 operation(s) for models.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Martian Gateway Chat Completions Streaming (HTTP + SSE)](https://apis.io/asyncapis/martian-ai/martian-ai-asyncapi/)

#### Event channels (1)

Individual events and webhooks the provider emits.

- [/v1/chat/completions](https://apis.io/channels/martian-ai/v1-chat-completions/)

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [martian-gateway](https://apis.io/servers/martian-ai/martian-gateway/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Martian Ai Agentic Access](https://apis.io/agentic-access/martian-ai/martian-ai-agentic-access/)

#### Collections (4)

Postman and Open Collection request collections.

- [Martian Gateway API](https://apis.io/collections/martian-ai/open-martian-ai/)
- [Martian Gateway Chat Completions API](https://apis.io/collections/martian-ai/open-martian-ai-chat-completions-api/)
- [Martian Gateway Chat Completions Messages API](https://apis.io/collections/martian-ai/open-martian-ai-messages-api/)
- [Martian Gateway Chat Completions Models API](https://apis.io/collections/martian-ai/open-martian-ai-models-api/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Martian — asyncapi rules](https://apis.io/rules/martian-ai/martian-ai-asyncapi-spectral-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Martian Ai Authentication](https://apis.io/security/martian-ai/martian-ai-authentication/)
- [Martian Ai Domain Security](https://apis.io/security/martian-ai/martian-ai-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Martian Ai Plans Pricing](https://apis.io/plans/martian-ai/martian-ai-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Martian Ai Rate Limits](https://apis.io/rate-limits/martian-ai/martian-ai-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Martian Ai Finops](https://apis.io/finops/martian-ai/martian-ai-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.withmartian.com)
- [Documentation](https://docs.withmartian.com)
- [Getting started](https://docs.withmartian.com/quickstart)
- [API reference](https://docs.withmartian.com/api-reference)
- [Sign up](https://app.withmartian.com/)
- [Support](https://docs.withmartian.com/resources/support)
- [Blog](https://www.withmartian.com/blog)
- [GitHub](https://github.com/withmartian)
- [Status](https://status.withmartian.com)

## API Evangelist rating

**Kin Score 44.3** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 73.2 |
| Contract quality | 57.6 |
| Contract governance | 29.5 |
| Operational transparency | 18.4 |
| Developer ergonomics | 65.5 |
| Access clarity | 21.1 |

**Agent readiness 21.1** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | documented (partial credit) |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | derived (partial credit) |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | — |
| Operation Distinctiveness | na |

**Regulatory alignment 15.5** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/martian-ai/](https://apis.io/providers/martian-ai/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Martian: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/martian-ai/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
