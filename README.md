# Universiti Kebangsaan Malaysia (ukm)

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
