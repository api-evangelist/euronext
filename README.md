# Euronext (euronext)

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
