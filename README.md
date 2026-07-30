# Koska

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
