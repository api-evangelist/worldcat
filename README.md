# WorldCat (worldcat)

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

OCLC WorldCat REST API for searching 500 million+ library holdings worldwide, accessing bibliographic records, finding library locations, and retrieving rich metadata for books, videos, music, and other media. Provides access to the WorldCat Search API, WorldCat Metadata API, WorldCat Knowledge Base API, and WorldCat Entities data API for libraries and developers building discovery and cataloging applications.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/worldcat/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/worldcat/refs/heads/main/apis.yml)

## Tags

- Libraries
- Bibliographic Records
- WorldCat
- OCLC
- Cataloging
- Metadata
- Discovery
- Books
- Media
- Linked Data

## Timestamps

- **Created:** 2026-06-13
- **Modified:** 2026-06-13

## APIs

### WorldCat Search API

Search WorldCat and retrieve bibliographic records for cataloged items such as books, videos, music and more across 500 million+ holdings. Supports retrieval by OCLC number, ISBN, ISSN, and other identifiers. Also enables finding libraries holding specific items and identifying libraries committed to retention programs.

- **Human URL:** [https://www.oclc.org/developer/api/oclc-apis/worldcat-search-api.en.html](https://www.oclc.org/developer/api/oclc-apis/worldcat-search-api.en.html)
- **Base URL:** `https://americas.discovery.api.oclc.org/worldcat/search/v2`

#### Tags

- Search
- Bibliographic Records
- WorldCat
- OCLC
- Libraries
- Holdings

#### Properties

- [Documentation](https://www.oclc.org/developer/api/oclc-apis/worldcat-search-api.en.html)
- [OpenAPI](https://developer.api.oclc.org/wcv2) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### WorldCat Metadata API

Enables libraries to search, retrieve and maintain their bibliographic, local bibliographic, holdings, and local holdings data in WorldCat. Supports synchronizing local catalog data, discovering shared print retention information, and enhancing metadata quality across the network.

- **Human URL:** [https://www.oclc.org/developer/api/oclc-apis/worldcat-metadata-api.en.html](https://www.oclc.org/developer/api/oclc-apis/worldcat-metadata-api.en.html)
- **Base URL:** `https://metadata.api.oclc.org/worldcat`

#### Tags

- Metadata
- Cataloging
- Holdings
- Bibliographic Records
- Libraries

#### Properties

- [Documentation](https://www.oclc.org/developer/api/oclc-apis/worldcat-metadata-api.en.html)
- [OpenAPI](https://developer.api.oclc.org/wc-metadata-v2) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### WorldCat Knowledge Base API

Provides developer-level access to a library's information in the WorldCat Knowledge Base, combining data about a library's e-content with access through linking features. Supports OpenURL requests for matching citations and retrieving access links, and REST requests for browsing and searching library subscription resources.

- **Human URL:** [https://www.oclc.org/developer/api/oclc-apis/worldcat-knowledge-base-api.en.html](https://www.oclc.org/developer/api/oclc-apis/worldcat-knowledge-base-api.en.html)
- **Base URL:** `https://worldcat.org/webservices/kb`

#### Tags

- Knowledge Base
- E-resources
- OpenURL
- Libraries
- Subscriptions

#### Properties

- [Documentation](https://www.oclc.org/developer/api/oclc-apis/worldcat-knowledge-base-api.en.html)

### WorldCat Entities Data API

Retrieve a set of properties and data for over 150 million WorldCat Entities using associated uniform resource identifiers (URIs). Supports linked data integration for local discovery applications, research and analysis, and monitoring updates to WorldCat Entities data.

- **Human URL:** [https://www.oclc.org/developer/api/oclc-apis/worldcat-entities-data.en.html](https://www.oclc.org/developer/api/oclc-apis/worldcat-entities-data.en.html)
- **Base URL:** `https://id.oclc.org/worldcat/entity`

#### Tags

- Entities
- Linked Data
- WorldCat
- Libraries
- Research

#### Properties

- [Documentation](https://www.oclc.org/developer/api/oclc-apis/worldcat-entities-data.en.html)
- [OpenAPI](https://developer.api.oclc.org/entity-data) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

## Common Properties

- [Website](https://www.worldcat.org/)
- [Documentation](https://www.oclc.org/developer/api/oclc-apis.en.html)
- [Git Hub Org](https://github.com/OCLC-Developer-Network)
- [LinkedIn](https://www.linkedin.com/company/oclc)
- [Blog](https://www.oclc.org/developer/news.en.html)
- [Pricing](https://www.oclc.org/en/membership/fees.html)
- [Status Page](https://oclc.service-now.com/status)
- [X (Twitter)](https://x.com/oclcdevnetwork)
- [Plans](plans/worldcat-plans-pricing.yml)
- [Rate Limits](rate-limits/worldcat-rate-limits.yml)
- [Fin Ops](finops/worldcat-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
