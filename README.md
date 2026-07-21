# Euronext (euronext)

Euronext N.V. is the leading pan-European exchange operator, running regulated cash and derivatives markets in Amsterdam, Brussels, Dublin, Lisbon, Milan, Oslo, and Paris, and owning Borsa Italiana and power exchange Nord Pool. Its market data arm sells real-time, delayed, historical, index, and reference data through the low-latency Optiq Market Data Gateway (UDP multicast SBE feed, also cloud-delivered), Optiq flat files, and the Euronext Web Services JSON API, alongside the Saturn REST API for MiFID II regulatory reporting. All access is sales-gated and entitlement-managed - client specifications are published as public PDFs but base URLs and tokens are issued only at onboarding, with no self-serve developer portal.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/euronext/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/euronext/refs/heads/main/apis.yml)

## Tags

- Financial
- Market Data
- Stocks
- Exchange
- Real-Time
- Historical Data
- Indices
- Reference Data
- Derivatives
- Regulatory Reporting

## Timestamps

- **Created:** 2026-07-21
- **Modified:** 2026-07-21

## APIs

### Euronext Web Services Market Data API

On-demand real-time, delayed, and reference market data over HTTP in JSON (REST) covering equities, fixed income, ETFs and funds, warrants and certificates, derivatives, commodities, and indices, with intraday interval-bar aggregation. Token authentication; the endpoint URL and user token are issued by Euronext at onboarding and no public base URL is documented.

- **Human URL:** [https://www.euronext.com/en/data/how-access-market-data/web-services](https://www.euronext.com/en/data/how-access-market-data/web-services)

#### Tags

- Market Data
- Real-Time
- Delayed
- Quotes
- Trades

#### Properties

- [Documentation](https://www.euronext.com/en/data/how-access-market-data/web-services)
- [API Reference](https://connect2.euronext.com/en/data/client-specifications)

### Euronext Web Services Historical Data API

End-of-day summary time series (open, high, low, close, last, volumes, turnover, capitalization) for indices and cash markets by ISIN and MIC, requested as JSON over HTTPS using POST only (GET unsupported). Documented in a public client-specification PDF; the request URL and key are provided by Euronext at onboarding.

- **Human URL:** [https://www.euronext.com/en/data/how-access-market-data/web-services](https://www.euronext.com/en/data/how-access-market-data/web-services)

#### Tags

- Historical Data
- End of Day
- Time Series

#### Properties

- [Documentation](https://www.euronext.com/en/data/how-access-market-data/web-services)
- [API Reference (Client Specification PDF)](https://connect2.euronext.com/sites/default/files/documentation/data/ews_api_-_historical_data_client_specification.pdf)

### Euronext Web Services Indices API

Index-level data for Euronext indices delivered through the Euronext Web Services JSON API, documented in a dedicated public client-specification PDF. Access is contracted through Euronext Market Data with tokens issued at integration time.

- **Human URL:** [https://www.euronext.com/en/data/how-access-market-data/web-services](https://www.euronext.com/en/data/how-access-market-data/web-services)

#### Tags

- Indices
- Index Data
- Reference Data

#### Properties

- [Documentation](https://www.euronext.com/en/data/how-access-market-data/web-services)
- [API Reference (Client Specification PDF)](https://connect2.euronext.com/sites/default/files/documentation/data/EWS%20API%20-%20Indices%20-%20Client%20Specification_v1.3_27.01.2020.pdf)

### Euronext Saturn Reporting API

REST web services for the Saturn global reporting solution covering MiFID II transaction reporting, trade submission (NEW, AMEND, CANCEL), and commodities positions reporting in JSON, XML, and CSV. HTTPS logon returns a token carried in the Authorization header; user accounts are requested through market-access@euronext.com, so access is member-gated.

- **Human URL:** [https://connect.euronext.com/en/it-documentation](https://connect.euronext.com/en/it-documentation)

#### Tags

- Regulatory Reporting
- MiFID II
- Trade Reporting
- Post-Trade

#### Properties

- [Documentation](https://connect.euronext.com/en/it-documentation)
- [API Reference (Web Services Specification PDF)](https://www.euronext.com/sites/www.euronext.com/files/euronext-saturn-web_services_specifications_2.8.8.pdf)

### Euronext Optiq Market Data Gateway (MDG)

Low-latency real-time market data feed for Euronext cash and derivatives markets delivered as UDP multicast messages in Simple Binary Encoding (SBE) with LZ4-compressed snapshots, plus an MDG Lite variant and cloud delivery. Not an HTTP API - interface specifications are published as public PDFs on Euronext Connect and access requires a market data agreement and connectivity provisioning.

- **Human URL:** [https://www.euronext.com/en/data/how-access-market-data/euronext-optiq-mdg-cloud](https://www.euronext.com/en/data/how-access-market-data/euronext-optiq-mdg-cloud)

#### Tags

- Streaming
- Multicast
- SBE
- Low Latency
- Order Book

#### Properties

- [Documentation](https://www.euronext.com/en/data/how-access-market-data/euronext-optiq-mdg-cloud)
- [API Reference (IT Documentation)](https://connect.euronext.com/en/it-documentation)

## Common Properties

- [Website](https://www.euronext.com/)
- [Portal](https://connect.euronext.com/)
- [Documentation](https://connect.euronext.com/en/it-documentation)
- [GitHub Organization](https://github.com/euronext)
- [LinkedIn](https://www.linkedin.com/company/euronext)
- [Blog](https://www.euronext.com/en/news)
- [Support](https://www.euronext.com/en/contact)
- [Terms of Service](https://www.euronext.com/en/terms-use)
- [Privacy Policy](https://www.euronext.com/en/privacy-statement)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
