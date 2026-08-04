# QuoteMedia (quotemedia)

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

QuoteMedia, Inc. is an independent, publicly traded (OTC QMCI) financial market data and financial technology company headquartered in Fountain Hills, Arizona, founded in 1999. It licenses real-time, delayed, and historical market data - equities, options, futures, commodities, currencies, mutual funds, ETFs, and indices - plus fundamentals, news, SEC/SEDAR filings, corporate actions, earnings, fund research, and ESG data to brokerages, banks, media, and investor relations customers. Data is delivered through the QuoteMedia OnDemand (QMOD) cloud REST API in JSON, XML, and CSV, an enterprise tick-by-tick Streaming Data Feed with WebSocket, Java, and .NET APIs, and bulk file services over SFTP. Access is entitlement-managed via webmaster IDs provisioned through sales, with a Quotestream Connect self-service package for individual developers; detailed API reference documentation lives behind a login on the company's Freshdesk knowledge base.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/quotemedia/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/quotemedia/refs/heads/main/apis.yml)

## Tags

- Financial
- Market Data
- Stocks
- Options
- Real-Time
- Streaming
- News
- Fundamentals
- Reference Data

## Timestamps

- **Created:** 2026-07-21
- **Modified:** 2026-07-21

## APIs

### QuoteMedia OnDemand (QMOD) Data API

Cloud-based request/response REST API delivering real-time and delayed Level 1/Level 2 quotes, trades, historical OHLCV and tick data, full option chains with Greeks, fundamentals, earnings, news from 300+ sources, SEC and SEDAR filings, corporate actions, fund data, insider and institutional ownership, ESG ratings, and master/reference data over HTTPS in JSON, XML, and CSV. The base host is live (endpoints such as getQuotes.json respond publicly) but every call requires a sales-provisioned Webmaster ID and entitlements; the full endpoint reference is behind the Freshdesk knowledge-base login.

- **Human URL:** [https://www.quotemedia.com/apifeeds](https://www.quotemedia.com/apifeeds)
- **Base URL:** `https://app.quotemedia.com/data`

#### Tags

- Market Data
- Quotes
- Options
- Fundamentals
- News
- REST

#### Properties

- [Documentation](https://www.quotemedia.com/apifeeds)
- [Documentation — QuoteMedia OnDemand brochure](https://brochures.quotemedia.com/quotemedia-on-demand)
- [Documentation — Data Feed Solutions](https://quotemedia.com/solutions/data-feed)

### QuoteMedia Streaming Data Feed API

Enterprise tick-by-tick streaming feed for real-time or delayed Level 1 and Level 2 market data, normalized across exchanges and delivered through a WebSocket API plus Java and .NET client APIs. The company's QMZ (QuoteMedia Zero) offering delivers real-time price data with consolidated US volume over the same streaming API without exchange license agreements. Sales-gated; no public endpoint hosts or protocol reference are published.

- **Human URL:** [https://quotemedia.com/solutions/data-feed](https://quotemedia.com/solutions/data-feed)

#### Tags

- Streaming
- WebSocket
- Level 2
- Tick Data

#### Properties

- [Documentation](https://quotemedia.com/solutions/data-feed)

### QuoteMedia File Services

Bulk data delivery via SFTP flat files for systematic import of price data, financials, corporate actions, and fund data, alongside historical time-series downloads in CSV, XML, and JSON. Sales-gated enterprise service documented at the marketing level only.

- **Human URL:** [https://quotemedia.com/solutions/data-feed](https://quotemedia.com/solutions/data-feed)

#### Tags

- Flat Files
- SFTP
- End of Day
- Corporate Actions

#### Properties

- [Documentation](https://quotemedia.com/solutions/data-feed)

### Quotestream Connect for Developers

Self-service package for non-professional developers building personal applications, combining tick-by-tick streaming data with request APIs, developer kits with documentation and example code, 90 days of intraday history, EOD data, futures continuation data, and symbol lookup. The documentation articles on the QuoteMedia support portal require a login (they redirect to Freshworks OAuth), so the developer kit contents are not publicly browsable.

- **Human URL:** [https://support.quotemedia.com/support/solutions/articles/13000091019-quotestream-connect-for-developers](https://support.quotemedia.com/support/solutions/articles/13000091019-quotestream-connect-for-developers)

#### Tags

- Developers
- Streaming
- Request API
- Self-Service

#### Properties

- [Documentation](https://support.quotemedia.com/support/solutions/articles/13000091019-quotestream-connect-for-developers)

## Common Properties

- [Website](https://quotemedia.com/)
- [Portal](https://www.quotemedia.com/apifeeds)
- [Documentation](https://quotemediasupport.freshdesk.com/support/home)
- [Support](https://quotemediasupport.freshdesk.com/support/home)
- [Status Page](https://status.quotemedia.com)
- [Blog](https://quotemedia.com/company/blog)
- [LinkedIn](https://www.linkedin.com/company/quotemedia)
- [Terms of Service](https://quotemedia.com/legal/tos)
- [Privacy Policy](https://quotemedia.com/legal/privacy-policy)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
