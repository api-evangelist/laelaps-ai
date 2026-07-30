# Laelaps AI

Laelaps AI builds a hardware-agnostic, fail-safe autonomous security layer that unifies aerial, ground, and stationary robots with a site's existing fixed cameras into one coordinated monitoring force — combining field foundational models, visual intelligence, and multi-agent coordination for continuous surveillance, rapid response, and autonomous dispatch across commercial and defense sites.

- Website: https://laelaps.ai/
- Legal entity: Laelaps AI Ltd (UK company no. 15375693), with operations in Zurich, Switzerland
- Founders: Dr. Sophia Belser (CEO), Dr. Maria Stamatopoulou (CRO), Rokas Bendikas (CTO)
- Backed by: Speedinvest, Expeditions Fund, Florent Venture Partners, Fund F, ESA BIC Switzerland, NVIDIA Inception

## API surface

Laelaps AI publishes **no public API** as of 2026-07-19 — no developer portal, documentation,
API reference, SDKs, CLI, changelog, status page, or machine-readable API description
(OpenAPI / AsyncAPI / GraphQL) was found. The enrichment pipeline therefore captured
identity plus what could be honestly probed:

- `security/laelaps-ai-domain-security.yml` — probed TLS/HSTS/DNS posture (TLS 1.3, HSTS 2y, CAA, SPF, DMARC `p=reject`)
- `well-known/laelaps-ai-well-known.yml` — recorded `/.well-known/` probe (all 404)
- `llms/laelaps-ai-llms.txt` — generated llms.txt for the company profile
