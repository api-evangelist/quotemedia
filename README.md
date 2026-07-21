# QuoteMedia (quotemedia)

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
