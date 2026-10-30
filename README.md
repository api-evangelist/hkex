# HKEX

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

HKEX (Hong Kong Exchanges and Clearing Limited, SEHK 388) operates the Stock Exchange of Hong Kong, the Hong Kong Futures Exchange, and their clearing houses, and also owns the London Metal Exchange. As an exchange data arm it sells real-time securities and derivatives market data through the sales-gated HKEX Orion Market Data (OMD) platform - binary multicast datafeeds licensed to vendors and subscribers rather than a self-serve HTTP API - plus historical tick, full order book, and CCASS shareholding reference data through the HKEX Data Marketplace, delivered via SFTP, cloud-to-cloud transfer, and direct download. Its one publicly documented RESTful JSON API is the FINI API Gateway for IPO settlement workflows, restricted to registered market participants using OAuth 2.0 JWT credentials.

**Areas:** Finance · Market Data · Stocks · Derivatives · Exchange · Real-Time · Historical Data · Order Book · Reference Data · IPO

## HKEX on APIs.io

Everything profiled for HKEX is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/hkex/](https://apis.io/providers/hkex/)** — or go straight to one of the APIs or properties below.

### APIs (4)

- [HKEX Orion Market Data Platform - Securities Market (OMD-C)](https://apis.io/apis/hkex/hkex-orion-market-data-securities-omd-c/) — Real-time datafeeds (OMD-C SS, SP, SF tiers) for all securities traded on the Stock Exchange of Hong Kong, published in a proprietary binary message format…
- [HKEX Orion Market Data Platform - Derivatives Market (OMD-D)](https://apis.io/apis/hkex/hkex-orion-market-data-derivatives-omd-d/) — Real-time datafeeds (OMD-D DS, DP, DF tiers) for futures and options traded on the Hong Kong Futures Exchange, delivered in binary format over IP…
- [HKEX Data Marketplace Historical Data](https://apis.io/apis/hkex/hkex-data-marketplace-historical-data/) — Web-based storefront for HKEX historical and reference data straight from the exchange - historical full order book tick data for securities and derivatives…
- [HKEX FINI API](https://apis.io/apis/hkex/hkex-fini-api/) — The FINI (Fast Interface for New Issuance) API Gateway offers RESTful JSON endpoints (e.g. GET /api/ipos/list/v1, GET /api/ipos/refdata/v1) for market…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Hkex Authentication](https://apis.io/security/hkex/hkex-authentication/)
- [Hkex Domain Security](https://apis.io/security/hkex/hkex-domain-security/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Hkex Scopes](https://apis.io/scopes/hkex/hkex-scopes/)

#### Rate limits (1)

Published request limits.

- [Hkex Rate Limits](https://apis.io/rate-limits/hkex/hkex-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.hkex.com.hk/)
- [Documentation](https://www.hkex.com.hk/Services/Market-Data-Services?sc_lang=en)
- [Pricing](https://www.hkex.com.hk/Services/Rules-and-Forms-and-Fees/Fees/Overview?sc_lang=en)
- [Support](https://www.hkex.com.hk/Global/Exchange/Contact?sc_lang=en)
- [Blog](https://www.hkexgroup.com/Media-Centre/Insight?sc_lang=en)
- [Terms of service](https://www.hkex.com.hk/Global/Exchange/Terms-of-Use?sc_lang=en)
- [Privacy policy](https://www.hkex.com.hk/Global/Exchange/HKEX-Privacy-Notices?sc_lang=en)

## API Evangelist rating

**Kin Score 30.3** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 62.5 |
| Contract quality | 0.0 |
| Contract governance | 18.2 |
| Operational transparency | 36.8 |
| Developer ergonomics | 45.2 |
| Access clarity | 31.6 |

**Agent readiness 7.9** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | — |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | documented (partial credit) |
| OpenAPI Examples | — |
| Rate Limit Signal | documented (partial credit) |
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

**Regulatory alignment 32.4** — Securities & Market Data

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/hkex/](https://apis.io/providers/hkex/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for HKEX: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/hkex/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
