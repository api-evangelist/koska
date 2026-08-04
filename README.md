# Koska

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

KOSKA Corporation (株式会社KOSKA) is a Tokyo-based manufacturing technology company, founded in October 2018, that applies cost accounting and IoT to the Japanese factory floor.

Its flagship product **GenKan** (原価管理自動化サービス) automates cost management for high-mix low-volume manufacturers: RFID and power sensors installed on existing equipment capture work progress and consumption without changing operator behavior, then make processing cost, material cost, and electricity cost visible line by line.

A second product, **ながら記録 (Nagara Kiroku / vScribe)**, is an AI record-keeping app for manufacturing, construction, and logistics sites — photograph a paper form and AI generates the input form, then operators record hands-free by speaking.

- Website: https://koska.jp
- Product (GenKan): https://koska.jp
- Product (ながら記録): https://vscribe.koska.jp/
- Company: https://koska.jp/info/

Backed by: 500-global

## API status

KOSKA publishes **no public developer API, SDK, CLI, developer portal, or `/.well-known/` discovery surface** as of 2026-07-19. It is a sensor-and-SaaS product company rather than an API provider. What this repo captures:

| Artifact | Method | Notes |
|---|---|---|
| `llms/koska-llms.txt` | searched | Verbatim from https://vscribe.koska.jp/llms.txt |
| `well-known/koska-well-known.yml` | searched | All `/.well-known/*` probes returned 404 (recorded) |
| `security/koska-domain-security.yml` | probed | TLS 1.3 both hosts; HSTS on koska.jp; SPF + DMARC `p=reject`; no DNSSEC, no CAA |
