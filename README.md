# HKEX (hkex)

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
