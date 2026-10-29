# Civic

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

Civic is a digital identity and security platform offering authentication, identity verification, and AI agent security infrastructure. Core products include Civic Hub (a Model Context Protocol gateway with guardrails, audit logging, secret management, and instant revocation for AI agents connecting to tools), Civic Auth (OAuth 2.0 / PKCE authentication for web and mobile apps with email, Google, and Web3 wallet sign-in plus embedded wallets on Solana and EVM chains), and Civic Labs (open-source agent infrastructure components). Originally known as a Web3 identity and KYC verification platform issuing Civic Passes (non-transferable on-chain tokens representing verified user attributes), Civic has evolved into a broader agent security layer. The Hub MCP gateway exposes a single Streamable HTTP endpoint backed by 80+ pre-built MCP server integrations and is compatible with 23+ AI agent frameworks.

**Areas:** AI Agents · Authentication · Digital Identity · Identity Verification · KYC · MCP · Security · Solana · Web3 · Wallets

## Civic on APIs.io

Everything profiled for Civic is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/civic/](https://apis.io/providers/civic/)** — or go straight to one of the APIs or properties below.

### APIs (4)

- [Civic Hub MCP API](https://apis.io/apis/civic/civic-hub-mcp-api/) — Civic Hub is a Model Context Protocol gateway that provides AI agents with secure, audited access to 80+ external tools and services through a single…
- [Civic Auth API](https://apis.io/apis/civic/civic-auth-api/) — Civic Auth provides OAuth 2.0 and PKCE-based authentication for web and mobile applications with support for email, Google, and Web3 wallet sign-in.…
- [Civic Pass API](https://apis.io/apis/civic/civic-pass-api/) — Issue and manage Civic Passes
- [Civic Piirequest API](https://apis.io/apis/civic/civic-piirequest-api/) — Get user PII and approve / reject receipt of PII

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Civic Agentic Access](https://apis.io/agentic-access/civic/civic-agentic-access/)

#### JSON Schema (1)

The data models the API reads and writes.

- [Civic Pass Customer API Schemas](https://apis.io/schemas/civic/civic-pass-customer-api/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Civic Pass Context](https://apis.io/jsonld/civic/civic-pass-context/)

#### Examples (5)

Example requests and responses.

- [Civic Pass Get](https://apis.io/examples/civic/civic-pass-get/)
- [Civic Pass Issue](https://apis.io/examples/civic/civic-pass-issue/)
- [Civic Pass List](https://apis.io/examples/civic/civic-pass-list/)
- [Civic Pass Update](https://apis.io/examples/civic/civic-pass-update/)
- [Civic Pii Get](https://apis.io/examples/civic/civic-pii-get/)

#### Collections (4)

Postman and Open Collection request collections.

- [Civic Customer pass API](https://apis.io/collections/civic/open-civic-pass-api/)
- [Civic Customer pass piirequest API](https://apis.io/collections/civic/open-civic-piirequest-api/)
- [Civic Customer pass API](https://apis.io/collections/civic/postman-civic-pass-api/)
- [Civic Customer pass piirequest API](https://apis.io/collections/civic/postman-civic-piirequest-api/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Civic — jsonschema rules](https://apis.io/rules/civic/civic-jsonschema-spectral-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Civic Authentication](https://apis.io/security/civic/civic-authentication/)
- [Civic Domain Security](https://apis.io/security/civic/civic-domain-security/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Civic Scopes](https://apis.io/scopes/civic/civic-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Civic Plans Pricing](https://apis.io/plans/civic/civic-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Civic Rate Limits](https://apis.io/rate-limits/civic/civic-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Civic Finops](https://apis.io/finops/civic/civic-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.civic.com/)
- [Documentation](https://docs.civic.com/)
- [Getting started](https://docs.civic.com/civic/quickstart)
- [Pricing](https://www.civic.com/pricing/)
- [Changelog](https://docs.civic.com/civic/changelog)
- [Blog](https://www.civic.com/blog/)
- [Security](https://docs.civic.com/civic/reference/security)
- [GitHub](https://github.com/civicteam)

## API Evangelist rating

**Kin Score 45.3** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 66.1 |
| Contract quality | 56.6 |
| Contract governance | 9.8 |
| Operational transparency | 34.2 |
| Developer ergonomics | 63.1 |
| Access clarity | 31.6 |

**Agent readiness 27.4** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | negotiable (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | verified |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | distinct |

**Regulatory alignment 24.1** — Payments

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/civic/](https://apis.io/providers/civic/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Civic: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/civic/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
