# pfSense (pfsense)

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

pfSense is an open-source firewall and router operating system based on FreeBSD, developed and maintained by Netgate, providing stateful firewall, routing, VPN (IPsec, OpenVPN, WireGuard), captive portal, traffic shaping, and IDS/IPS capabilities for home and enterprise networks. It is available as pfSense Community Edition (CE) and pfSense Plus, both managed via a web UI. The unofficial pfSense-pkg-RESTAPI package adds a REST and GraphQL API with 200+ endpoints under /api/v2 for automating firewall management, authenticated via local users, API keys, or JWT.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/pfsense/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/pfsense/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Firewall
- Network Security
- Router
- VPN
- Open Source
- FreeBSD
- Netgate

## Timestamps

- **Created:** 2026-05-11
- **Modified:** 2026-05-11

## APIs

### pfSense REST API (pfSense-pkg-RESTAPI)

Community-maintained REST and GraphQL API package for pfSense CE and pfSense Plus exposing 200+ endpoints under /api/v2 for firewall, interface, service, user, and system management. Authentication supports local user credentials, API keys, and JWT bearer tokens; the base URL is the pfSense instance's own hostname.

- **Human URL:** [https://pfrest.org/](https://pfrest.org/)
- **Base URL:** `https://pfsense.local/api/v2`

#### Tags

- Firewall API
- Network Automation
- REST
- GraphQL

#### Properties

- [Documentation](https://pfrest.org/)
- [A P I  Documentation](https://pfrest.org/api-docs/)
- [GitHub Repository](https://github.com/jaredhendrickson13/pfsense-api)
- [Contributing](https://pfrest.org/CONTRIBUTING/)
- [Postman Collection](collections/pfsense.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/pfsense.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://www.pfsense.org/)
- [Documentation](https://docs.netgate.com/pfsense/en/latest/)
- [Pricing](https://www.netgate.com/pfsense-plus-software)
- [Download](https://www.pfsense.org/download/)
- [GitHub Organization](https://github.com/pfsense)
- [Vendor](https://www.netgate.com/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
