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

Universiti Kebangsaan Malaysia (UKM), The National University of Malaysia, is a public research university in Bangi, Selangor, established 1970 ([ROR 00bw8d226](https://ror.org/00bw8d226)). This repository catalogs UKM's public, machine-readable footprint as an [APIs.json](http://apisjson.org) profile, under the API Evangelist **university** pipeline — which settles *who operates* each surface before saving anything.

UKM publishes no developer portal, no API documentation, no OpenAPI, no changelog and no status page. What it does operate, unauthenticated and on its own domain, is four machine-readable surfaces it has never described anywhere: a SAML 2.0 identity provider, two OAI-PMH 2.0 endpoints, and an open WordPress `wp/v2` REST API on two installations.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/ukm/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=ukm-api-evangelist&utm_content=repo

## Type

- university / Public Research University
- Index
- Consumer
- Public

## Tags

University, Higher Education, Education, Research, Malaysia, Southeast Asia, Identity Federation, SAML, Research Repository, Institutional Repository, OAI-PMH, Open Access, Scholarly Publishing, Library, Theses

## Surfaces

Every entry carries an `x-operator`. `institution` means UKM runs the thing the contract describes; `registry` means UKM is registered in someone else's registry; `tenant` means UKM's account on a vendor's platform, where the data is UKM's and the contract is the vendor's.

### institution

- **SSO@UKM — SAML 2.0 Identity Provider** — SimpleSAMLphp IdP publishing unauthenticated SAML 2.0 metadata. In production (libquest.ukm.my is a registered SP). Not in eduGAIN.
  - Metadata: https://sso.ukm.my/saml2/idp/metadata.php
  - [openapi/ukm-identity-federation-openapi.yml](openapi/ukm-identity-federation-openapi.yml)
- **UKM Learning and Research Repository (OAI-PMH)** — DSpace 6.3, twelve metadata formats, run by Perpustakaan Tun Seri Lanang.
  - OAI-PMH: https://ptsldigital.ukm.my/oai/request?verb=Identify
  - [openapi/ukm-ptsl-digital-oai-pmh-openapi.yml](openapi/ukm-ptsl-digital-oai-pmh-openapi.yml)
- **UKM e-Journal System (OAI-PMH)** — Open Journal Systems 2.4.8.1, five metadata formats, 100 sets. Not previously catalogued.
  - OAI-PMH: https://ejournal.ukm.my/index.php/index/oai?verb=Identify
  - [openapi/ukm-ejournal-oai-pmh-openapi.yml](openapi/ukm-ejournal-oai-pmh-openapi.yml)
- **UKM Web Content REST API (WordPress wp/v2)** — 314 routes, unauthenticated reads, two installations. Undocumented and ungoverned.
  - Route index: https://www.ukm.my/portal/wp-json/
  - [openapi/ukm-web-content-rest-openapi.yml](openapi/ukm-web-content-rest-openapi.yml)
- **UKM Journal Article Repository (OAI-PMH) — unreachable** — EPrints repository registered in OpenDOAR and ROAR. `journalarticle.ukm.my` resolves but has not answered on port 80 or 443 since at least June 2026. Retained as a fact; its dead pointers were removed.
  - Registry: https://opendoar.ac.uk/repository/2122

### registry

- **Crossref DOI Registration** — three memberships owned by UKM units, 16,447 DOIs: [7332 UKM Press](https://api.crossref.org/members/7332) (10.17576), [8124 Faculty of Medicine](https://api.crossref.org/members/8124) (10.17845), [11019 Research Centre for Sharia](https://api.crossref.org/members/11019) (10.26475).
- **ROR Organization Registration** — https://ror.org/00bw8d226

### tenant

- **Springshare LibGuides** — https://ukm.libguides.com/ — relationship recorded, vendor contract not saved.
- **RemoteXs E-Resources Proxy** — https://eresourcesptsl.ukm.remotexs.co/ — relationship recorded, vendor contract not saved.

## Artifacts

- OpenAPI: [openapi/](openapi/) (pristine pre-refine copies in [openapi/_original/](openapi/_original/))
- JSON Schema: [json-schema/ukm-wordpress-page-schema.json](json-schema/ukm-wordpress-page-schema.json)
- Examples: [examples/](examples/)
- Conformance: [conformance/ukm-conformance.yml](conformance/ukm-conformance.yml)
- Authentication: [authentication/ukm-authentication.yml](authentication/ukm-authentication.yml)
- Errors: [errors/ukm-errors.yml](errors/ukm-errors.yml)
- Lifecycle: [lifecycle/ukm-lifecycle.yml](lifecycle/ukm-lifecycle.yml)
- Vocabulary: [vocabulary/ukm-vocabulary.yml](vocabulary/ukm-vocabulary.yml)
- JSON-LD: [json-ld/ukm-context.jsonld](json-ld/ukm-context.jsonld)
- Plans: [plans/ukm-plans-pricing.yml](plans/ukm-plans-pricing.yml)
- Rate Limits: [rate-limits/ukm-rate-limits.yml](rate-limits/ukm-rate-limits.yml)
- FinOps: [finops/ukm-finops.yml](finops/ukm-finops.yml)
- Domain Security: [security/ukm-domain-security.yml](security/ukm-domain-security.yml)
- Review: [review.yml](review.yml)

## Domain standard conformance (education regime)

Evidenced from UKM's own surfaces only. See [conformance/ukm-conformance.yml](conformance/ukm-conformance.yml).

- **oai-pmh** — conformant, two live institution-operated endpoints.
- **saml** — conformant, with published gaps (non-URI entityID, unsigned metadata, transient NameID only).
- **crossref** — registered, three memberships.
- Not found: shibboleth, datacite, orcid, scim, lti, oneroster, ed-fi, caliper, qti.

## Timestamps

- Created: 2026-06-03
- Modified: 2026-09-01

## Common Properties

- Website: https://www.ukm.my/portal/
- Blog: https://www.ukm.my/beritaukm/ (RSS: https://www.ukm.my/beritaukm/feed/)
- API Reference: https://www.ukm.my/portal/wp-json/
- Identity Federation: https://sso.ukm.my/saml2/idp/metadata.php
- Research Repository: https://ptsldigital.ukm.my/ and https://ejournal.ukm.my/
- Library: https://www.ukm.my/ptsl/
- LinkedIn: https://www.linkedin.com/school/universitikebangsaanmalaysia/

## Notes

- Re-profiled 2026-09-01 under the university pipeline. Every OpenAPI in this repo was written by API Evangelist from live probes and is marked `method: probed` — UKM publishes none of its own.
- No vendor contract had been misattributed to UKM, so nothing was removed on that account. The two vendor tenancies found are recorded as relationships only.
- Every pointer emitted here was fetched and confirmed live on 2026-09-01. Dead pointers to `journalarticle.ukm.my` were removed; the stale `www.ukm.my/portalukm/` Website pointer was corrected to `www.ukm.my/portal/`.
- `www.ukm.my` returns 404 for robots.txt, sitemap.xml, llms.txt and .well-known/security.txt. `sso.ukm.my` has no OpenID Connect discovery document.
- UKM is **not** registered in eduGAIN — all 10,615 entities were scanned on 2026-09-01 — while sixteen other Malaysian institutions are, via SIFULAN.
- Both scholarly platforms are years past end of support: DSpace 6.3 (EOL 2023) and OJS 2.4.8.1 (EOL 2020).
- No official UKM GitHub organization was found; `github.com/ukm` is an unrelated personal account and is deliberately excluded. `UKM-HEP` and `UKM-NUKE` are research-group orgs with no evidenced institutional endorsement and are not credited.
- No course catalog, timetable, registrar, open data portal, research computing surface or AI policy was found. No endpoints were fabricated.

## Maintainers

- Kin Lane — kin@apievangelist.com
