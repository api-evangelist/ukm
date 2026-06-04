# Universiti Kebangsaan Malaysia (ukm)

Universiti Kebangsaan Malaysia (UKM), The National University of Malaysia, is a public research university in Bangi, Selangor, ranked #138 in the QS World University Rankings 2025. This repository catalogs UKM's public, machine-readable developer/API footprint as an [APIs.json](http://apisjson.org) profile. UKM does not operate a general-purpose developer portal; its verifiable footprint is library-operated scholarly infrastructure exposing standards-based OAI-PMH interfaces.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/ukm/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=ukm-api-evangelist&utm_content=repo

## Type

- Index
- Consumer
- 3rd-Party

## Tags

Education, Higher Education, University, Research, Open Access, Institutional Repository, OAI-PMH, Library, Malaysia

## APIs

- **UKM Learning and Research Repository (OAI-PMH)** — DSpace institutional repository (theses, exam papers, government and law documents) with a live OAI-PMH 2.0 interface.
  - Docs: https://ptsldigital.ukm.my/
  - OAI-PMH: https://ptsldigital.ukm.my/oai/request?verb=Identify
- **UKM Journal Article Repository (OAI-PMH)** — EPrints repository of UKM faculty/institute/UKM Press journal articles; OAI-PMH 2.0 capable (registry-confirmed).
  - Docs: http://journalarticle.ukm.my/eprints/
  - OAI-PMH: http://journalarticle.ukm.my/cgi/oai2?verb=Identify
  - Registry: https://opendoar.ac.uk/repository/2122

## Plans

- [plans/ukm-plans-pricing.yml](plans/ukm-plans-pricing.yml)

## Rate Limits

- [rate-limits/ukm-rate-limits.yml](rate-limits/ukm-rate-limits.yml)

## FinOps

- [finops/ukm-finops.yml](finops/ukm-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.ukm.my/portalukm/
- LinkedIn: https://www.linkedin.com/school/universitikebangsaanmalaysia/
- Plans: [plans/ukm-plans-pricing.yml](plans/ukm-plans-pricing.yml)
- Rate Limits: [rate-limits/ukm-rate-limits.yml](rate-limits/ukm-rate-limits.yml)
- FinOps: [finops/ukm-finops.yml](finops/ukm-finops.yml)
- Review: [review.yml](review.yml)

## Notes

- All endpoints were probed on 2026-06-03. The DSpace OAI-PMH endpoint at `ptsldigital.ukm.my` returned a valid OAI-PMH 2.0 Identify response (HTTP 200).
- The EPrints UKM Journal Article Repository (`journalarticle.ukm.my`) is registry-confirmed (ROAR / OpenDOAR) as OAI-PMH 2.0 capable, but its host did not respond to automated probes during this review.
- No official UKM GitHub organization exists; `github.com/ukm` is an unrelated personal account and was deliberately excluded.
- Student/staff online services run behind institutional single sign-on and are not publicly documented. No endpoints were fabricated.

## Maintainers

- Kin Lane — kin@apievangelist.com
