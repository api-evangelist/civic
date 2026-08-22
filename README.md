# Civic (civic)

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

Digital identity and AI agent security platform. Civic provides authentication, identity verification, and secure connectivity infrastructure for web, mobile, and AI agent applications.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/civic/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/civic/refs/heads/main/apis.yml)

## Scope

- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- AI Agents
- Authentication
- Digital Identity
- Identity Verification
- KYC
- MCP
- OAuth
- Security
- Solana
- Web3
- Wallets

## Timestamps

- **Created:** 2026-06-14
- **Modified:** 2026-06-14

## APIs

### Civic Hub MCP API

Civic Hub is a Model Context Protocol gateway that provides AI agents with secure, audited access to 80+ external tools and services through a single Streamable HTTP endpoint (`https://app.civic.com/hub/mcp`). Authentication uses 30-day Bearer tokens. The gateway enforces least-privilege guardrails, logs every tool call, manages OAuth tokens for connected services, and supports instant access revocation.

#### Tags

- AI Agents
- Audit Logging
- Guardrails
- MCP
- Security

#### Properties

- [Documentation](https://docs.civic.com/)
- [Getting Started](https://docs.civic.com/civic/quickstart)
- [Authentication](https://docs.civic.com/civic/reference/security)
- [Changelog](https://docs.civic.com/civic/changelog)
- [Repository](https://github.com/civicteam/typescript-sdk)

### Civic Auth API

OAuth 2.0 and PKCE-based authentication for web and mobile apps. Supports email, Google, and Web3 wallet sign-in with embedded wallets on Solana and EVM chains. Available as `@civic/auth`, `@civic/auth-web3`, and `@civic/auth-mcp` npm packages. Integrates with Next.js, React, Express, Hono, and standard MCP server/client toolchains.

#### Tags

- Authentication
- Embedded Wallets
- MCP
- OAuth
- PKCE
- Solana
- Web3

#### Properties

- [Documentation](https://docs.civic.com/)
- [Getting Started](https://docs.civic.com/civic/quickstart)
- [Repository](https://github.com/civicteam/civic-auth-examples)
- [npm SDK (@civic/auth)](https://www.npmjs.com/package/@civic/auth)
- [npm SDK (@civic/auth-mcp)](https://www.npmjs.com/package/@civic/auth-mcp)
- [Repository (auth-mcp)](https://github.com/civicteam/auth-mcp)

### Civic Pass API

On-chain identity permissioning system that issues non-transferable Civic Passes representing verified user attributes (KYC, liveness, location). Passes are stored on Solana and EVM chains. Over 925,000 Civic Passes issued. Used for bot prevention, DeFi access control, KYC-gated token sales, and wallet attestation.

#### Tags

- Attestation
- Blockchain
- Identity Verification
- KYC
- Permissioning
- Solana
- Token-Gating
- Web3

#### Properties

- [Documentation](https://www.civic.com/)
- [Repository (Solana Attestation Service)](https://github.com/civicteam/solana-attestation-service)
- [Repository (Token2022 Transfer Hook)](https://github.com/civicteam/token-extensions-transfer-hook)
- [SDK (Legacy SIP)](https://github.com/civicteam/npm-civic-sip-api)

## Common Properties

- [Website](https://www.civic.com/)
- [Documentation](https://docs.civic.com/)
- [Getting Started](https://docs.civic.com/civic/quickstart)
- [Portal](https://app.civic.com)
- [Pricing](https://www.civic.com/pricing/)
- [Plans](plans/civic-plans-pricing.yml)
- [Rate Limits](rate-limits/civic-rate-limits.yml)
- [FinOps](finops/civic-finops.yml)
- [Blog](https://www.civic.com/blog/)
- [Changelog](https://docs.civic.com/civic/changelog)
- [GitHub Organization](https://github.com/civicteam)
- [Security](https://docs.civic.com/civic/reference/security)
- [Contact](mailto:bd@civic.com)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
