# SimpleHash (simplehash)

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

SimpleHash is an NFT data API aggregating metadata, ownership, transfers, floor prices, and token market data across 80+ blockchains. The platform provides REST API, webhook, and Kafka streaming access to 3B+ indexed tokens and NFTs, and is used at production scale by Coinbase, Phantom, Ledger, Uniswap, Rainbow, and many other leading wallets, marketplaces, and analytics platforms.

APIs.json: https://raw.githubusercontent.com/api-evangelist/simplehash/refs/heads/main/apis.yml

Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=simplehash-api-evangelist&utm_content=repo

---

## Tags

NFT, Blockchain, Web3, Cryptocurrency, Token, Metadata, Multi-chain, Ethereum, Solana, Base, Polygon

---

## APIs

| Name | Base URL | Description |
|------|----------|-------------|
| SimpleHash NFT & Token API | https://api.simplehash.com/api/v0 | Multi-chain REST API for NFT metadata, ownership, transfers, floor prices, listings, bids, spam scores, and fungible token market prices across 80+ blockchains. |

---

## Plans / Rate Limits / FinOps

| Resource | File |
|----------|------|
| Plans & Pricing | [plans/simplehash-plans-pricing.yml](plans/simplehash-plans-pricing.yml) |
| Rate Limits | [rate-limits/simplehash-rate-limits.yml](rate-limits/simplehash-rate-limits.yml) |
| FinOps | [finops/simplehash-finops.yml](finops/simplehash-finops.yml) |

**Plans summary:**
- **Starter** — Free, 25,000 requests/month, 100 requests/minute, up to 10 webhooks
- **Enterprise** — Custom pricing, custom rate limits, autoscaling, spam scores, dedicated support, committed-use discounts

**Authentication:** API key passed in the `X-Api-Key` HTTP header on every request.

---

## Timestamps

| Field | Value |
|-------|-------|
| Created | 2026-06-12 |
| Modified | 2026-06-12 |

---

## Common

| Type | URL |
|------|-----|
| Website | https://simplehash.com/ |
| Documentation | https://docs.simplehash.com/ |
| GitHub | https://github.com/simplehash |
| LinkedIn | https://www.linkedin.com/company/simplehash/ |
| Blog | https://simplehash.com/blog |
| Pricing | https://simplehash.com/pricing |
| Status Page | https://simplehash.betteruptime.com/ |
| X (Twitter) | https://x.com/SimpleHashInc |

---

## Maintainers

| Name | Email |
|------|-------|
| Kin Lane | kin@apievangelist.com |
