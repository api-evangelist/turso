# Turso (turso)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Turso is an edge database platform built on libSQL, a fork of SQLite, offering both an embedded in-process database engine and a managed cloud service for deploying millions of SQLite databases at the edge. Developers interact with Turso through the Platform API for database lifecycle management and the SQL over HTTP API for executing queries directly against edge-deployed databases. The platform targets multi-tenant SaaS, AI agent architectures, and edge/serverless workloads.

APIs.json: [https://raw.githubusercontent.com/api-evangelist/turso/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/turso/refs/heads/main/apis.yml)

Naftiko Run: [https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=turso-api-evangelist&utm_content=repo](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=turso-api-evangelist&utm_content=repo)

## Tags

- Database
- Edge Computing
- SQLite
- Developer Tools
- Multi-tenant
- AI Agents

## APIs

- **Turso Platform API** - RESTful management API for databases, groups, organizations, and tokens. [Documentation](https://docs.turso.tech/api-reference/introduction)
- **Turso SQL over HTTP API** - Execute SQL statements directly against edge-deployed databases over HTTP. [Documentation](https://docs.turso.tech/sdk/http/reference)
- **Turso AgentFS MCP Server** - Model Context Protocol server for AI assistant access to Turso databases. [Documentation](https://docs.turso.tech/agentfs/guides/mcp)

## Plans / Rate Limits / FinOps

- [Plans & Pricing](plans/turso-plans-pricing.yml)
- [Rate Limits](rate-limits/turso-rate-limits.yml)
- [FinOps](finops/turso-finops.yml)

## Timestamps

- Created: 2026-06-12
- Modified: 2026-06-12

## Common Properties

| Type | URL |
|------|-----|
| Website | https://turso.tech |
| Documentation | https://docs.turso.tech |
| GitHub Organization | https://github.com/tursodatabase |
| LinkedIn | https://www.linkedin.com/company/turso |
| X (Twitter) | https://x.com/tursodatabase |
| Blog | https://turso.tech/blog |
| Pricing | https://turso.tech/pricing |
| Status Page | https://status.turso.tech |
| SDKs | https://docs.turso.tech/sdk/introduction |
| CLI | https://github.com/tursodatabase/turso-cli |

## Maintainers

- Kin Lane / kin@apievangelist.com
