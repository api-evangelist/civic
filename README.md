# Civic (civic)

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
