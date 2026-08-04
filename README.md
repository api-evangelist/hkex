# HKEX (hkex)

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

HKEX (Hong Kong Exchanges and Clearing Limited, SEHK 388) operates the Stock Exchange of Hong Kong, the Hong Kong Futures Exchange, and their clearing houses, and also owns the London Metal Exchange. As an exchange data arm it sells real-time securities and derivatives market data through the sales-gated HKEX Orion Market Data (OMD) platform - binary multicast datafeeds licensed to vendors and subscribers rather than a self-serve HTTP API - plus historical tick, full order book, and CCASS shareholding reference data through the HKEX Data Marketplace, delivered via SFTP, cloud-to-cloud transfer, and direct download. Its one publicly documented RESTful JSON API is the FINI API Gateway for IPO settlement workflows, restricted to registered market participants using OAuth 2.0 JWT credentials.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/hkex/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/hkex/refs/heads/main/apis.yml)

## Tags

- Financial
- Market Data
- Stocks
- Derivatives
- Exchange
- Real-Time
- Historical Data
- Order Book
- Reference Data
- IPO

## Timestamps

- **Created:** 2026-07-21
- **Modified:** 2026-07-21

## APIs

### HKEX Orion Market Data Platform - Securities Market (OMD-C)

Real-time datafeeds (OMD-C SS, SP, SF tiers) for all securities traded on the Stock Exchange of Hong Kong, published in a proprietary binary message format over one-to-many IP multicast/UDP for high throughput and low latency. Not an HTTP API - access is licensed through HKEX data licensing agreements, and the binary interface specifications and connectivity guides are public PDFs.

- **Human URL:** [https://www.hkex.com.hk/Services/Market-Data-Services/Infrastructure/HKEX-Orion-Market-Data-Platform-Securities-Market-OMD-C?sc_lang=en](https://www.hkex.com.hk/Services/Market-Data-Services/Infrastructure/HKEX-Orion-Market-Data-Platform-Securities-Market-OMD-C?sc_lang=en)

#### Tags

- Market Data
- Real-Time
- Securities
- Multicast
- Order Book

#### Properties

- [Documentation](https://www.hkex.com.hk/Services/Market-Data-Services/Infrastructure/HKEX-Orion-Market-Data-Platform-Securities-Market-OMD-C?sc_lang=en)
- [API Reference — OMD-C Binary Interface Specifications (PDF)](https://www.hkex.com.hk/eng/prod/dataprod/Documents/HKEX_OMD-C_Binary_Interface_Specifications_v1.39b.pdf)

### HKEX Orion Market Data Platform - Derivatives Market (OMD-D)

Real-time datafeeds (OMD-D DS, DP, DF tiers) for futures and options traded on the Hong Kong Futures Exchange, delivered in binary format over IP multicast/UDP with separate channel sets for stock options and non-stock options markets. Licensed, sales-gated access; the binary interface specification and developers guide are public PDFs.

- **Human URL:** [https://www.hkex.com.hk/Services/Market-Data-Services/Infrastructure/HKEX-Orion-Market-Data-Platform-Derivatives-Market-OMD-D?sc_lang=en](https://www.hkex.com.hk/Services/Market-Data-Services/Infrastructure/HKEX-Orion-Market-Data-Platform-Derivatives-Market-OMD-D?sc_lang=en)

#### Tags

- Market Data
- Real-Time
- Derivatives
- Futures
- Options
- Multicast

#### Properties

- [Documentation](https://www.hkex.com.hk/Services/Market-Data-Services/Infrastructure/HKEX-Orion-Market-Data-Platform-Derivatives-Market-OMD-D?sc_lang=en)
- [API Reference — OMD-D Developers Guide (PDF)](https://www.hkex.com.hk/-/media/HKEX-Market/Services/Market-Data-Services/Infrastructure/HKEX-Orion-Market-Data-Platform-Derivatives-Market-OMD-D/HKEX-OMDD-Developers-Guide-v1,-d-,26.pdf)

### HKEX Data Marketplace Historical Data

Web-based storefront for HKEX historical and reference data straight from the exchange - historical full order book tick data for securities and derivatives (CSV), CCASS shareholding data, and securities attribute daily files. Delivered via SFTP, cloud-to-cloud transfer, or direct download; onboarding is handled through the datamarketplace@hkex.com.hk team rather than self-serve API keys, and no REST API is documented.

- **Human URL:** [https://data.hkex.com.hk/catalog](https://data.hkex.com.hk/catalog)

#### Tags

- Historical Data
- Tick Data
- Full Order Book
- Shareholding
- Reference Data

#### Properties

- [Portal](https://data.hkex.com.hk/catalog)
- [Documentation](https://www.hkex.com.hk/Services/Market-Data-Services/Historical-Data-Services/HKEX-Data-Marketplace?sc_lang=en)

### HKEX FINI API

The FINI (Fast Interface for New Issuance) API Gateway offers RESTful JSON endpoints (e.g. `GET /api/ipos/list/v1`, `GET /api/ipos/refdata/v1`) for market participants to automate IPO workflows - IPO reference data, EIPO subscriptions, and EIPO funding. Authentication uses OAuth 2.0 JWT-bearer grants against the HKEX Access Management server (`https://openam.connect.hkex.com.hk`) with registered RSA JSON Web Keys, TLS 1.2, and end-to-end payload encryption. Access is restricted to registered HKSCC participants, FINI banks, sponsors, and advisers - not open self-serve signup - but the API guide is a public PDF.

- **Human URL:** [https://www.hkex.com.hk/Services/Platform-Services/FINI?sc_lang=en](https://www.hkex.com.hk/Services/Platform-Services/FINI?sc_lang=en)

#### Tags

- IPO
- Settlement
- Reference Data
- REST
- Post-Trade

#### Properties

- [Documentation](https://www.hkex.com.hk/Services/Platform-Services/FINI?sc_lang=en)
- [API Reference — FINI API User Guide (PDF)](https://www.hkex.com.hk/-/media/HKEX-Market/Services/Next-Generation-Post-Trade-Programme/Fini/FINI-API-User-Guide-v0,-d-,41.pdf)

## Common Properties

- [Website](https://www.hkex.com.hk/)
- [Portal — HKEX Data Marketplace](https://data.hkex.com.hk/catalog)
- [Documentation — Market Data Services](https://www.hkex.com.hk/Services/Market-Data-Services?sc_lang=en)
- [LinkedIn](https://www.linkedin.com/company/hkex)
- [Blog — HKEX Insight](https://www.hkexgroup.com/Media-Centre/Insight?sc_lang=en)
- [Pricing — Fees Overview](https://www.hkex.com.hk/Services/Rules-and-Forms-and-Fees/Fees/Overview?sc_lang=en)
- [Terms of Service](https://www.hkex.com.hk/Global/Exchange/Terms-of-Use?sc_lang=en)
- [Privacy Policy](https://www.hkex.com.hk/Global/Exchange/HKEX-Privacy-Notices?sc_lang=en)
- [Support — Contact](https://www.hkex.com.hk/Global/Exchange/Contact?sc_lang=en)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
