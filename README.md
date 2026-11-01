# Universiti Kebangsaan Malaysia

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

Universiti Kebangsaan Malaysia (UKM), The National University of Malaysia, is a public research university in Bangi, Selangor, established 1970, ROR https://ror.org/00bw8d226. It publishes no developer portal, no API documentation, no OpenAPI, no changelog, no status page, no robots.txt, no sitemap.xml and no llms.txt — every one of those returns 404 on www.ukm.my. What it does operate, on its own domain and its own infrastructure, is four unauthenticated machine-readable surfaces that it has never described anywhere. The largest is its own identity provider: SSO@UKM at sso.ukm.my is a SimpleSAMLphp SAML 2.0 IdP publishing unauthenticated metadata with signing and encryption keys, SSO and SLO bindings and a technical contact, and it is demonstrably in production — the library's LibQuest service hands an unauthenticated visitor straight to it as SAML SP smuSSO-sp. UKM is nevertheless absent from eduGAIN; a scan of all 10,615 eduGAIN entities on 2026-09-01 found no ukm.my entity while sixteen other Malaysian institutions are registered through SIFULAN. The scholarly surfaces are two live OAI-PMH 2.0 endpoints run by Perpustakaan Tun Seri Lanang (the UKM Library): the DSpace 6.3 UKM Learning and Research Repository at ptsldigital.ukm.my with twelve metadata formats, and the OJS 2.4.8.1 UKM e-Journal System at ejournal.ukm.my with five formats and 100 sets — the latter never previously catalogued here. Both platforms are years past end of support. Behind them sits a real identifier footprint: three Crossref memberships owned by UKM units, led by UKM Press with prefix 10.17576 and 16,243 DOIs. A third repository, journalarticle.ukm.my, is registered in OpenDOAR and ROAR but has not answered on port 80 or 443 across probes in June and September 2026. The fourth surface is incidental rather than intentional: UKM runs its web estate on self-hosted WordPress and leaves the wp/v2 REST API open for unauthenticated reads — 314 routes on the main portal, a second installation on the Berita UKM news site. It is the closest thing the university has to a public read API for its own content, and nothing about it is documented or governed. Nothing in this profile is a vendor contract attributed to UKM. Two vendor tenancies are recorded as relationships only — Springshare LibGuides and a RemoteXs e-resources proxy. No course catalog, open data portal, research computing or library discovery API was found; the GEMILANG discovery service did not answer.

**Areas:** University · Higher Education · Education · Research · Malaysia · Southeast Asia · Identity Federation · SAML · Research Repository · Institutional Repository · OAI-PMH · Open Access

## Universiti Kebangsaan Malaysia on APIs.io

Everything profiled for Universiti Kebangsaan Malaysia is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/ukm/](https://apis.io/providers/ukm/)** — or go straight to one of the APIs or properties below.

### APIs (9)

- [UKM Journal Article Repository (OAI-PMH) — unreachable](https://apis.io/apis/ukm/journal-article-repository-oai/) — EPrints repository of journal articles published by UKM faculties, institutes and UKM Press, registered in OpenDOAR (record 2122) and ROAR as supporting…
- [Crossref DOI Registration (UKM Press and UKM faculties)](https://apis.io/apis/ukm/crossref-membership/) — Three Crossref memberships are held by units of Universiti Kebangsaan Malaysia, together accounting for 16,447 registered DOIs: member 7332, Penerbit…
- [ROR Organization Registration](https://apis.io/apis/ukm/ror-registration/) — Universiti Kebangsaan Malaysia is registered in the Research Organization Registry as https://ror.org/00bw8d226, created 2018-11-14 and last modified…
- [Springshare LibGuides (tenant deployment)](https://apis.io/apis/ukm/libguides-tenant/) — Perpustakaan Tun Seri Lanang runs its research and subject guides on a Springshare LibGuides tenant at ukm.libguides.com — an institution-specific subdomain…
- [RemoteXs E-Resources Proxy (tenant deployment)](https://apis.io/apis/ukm/remotexs-tenant/) — UKM Library's off-campus access to licensed e-resources runs on a RemoteXs tenant at eresourcesptsl.ukm.remotexs.co — a vendor host carrying a UKM-specific…
- [Universiti Kebangsaan Malaysia Metadata API](https://apis.io/apis/ukm/ukm-metadata-api/) — SAML 2.0 metadata publication.
- [Universiti Kebangsaan Malaysia OAI PMH API](https://apis.io/apis/ukm/ukm-oai-pmh-api/) — Open Archives Initiative Protocol for Metadata Harvesting, version 2.0.
- [Universiti Kebangsaan Malaysia Single Sign-On API](https://apis.io/apis/ukm/ukm-single-sign-on-api/) — SAML 2.0 browser SSO and single logout profiles.
- [Universiti Kebangsaan Malaysia Website (WordPress REST)](https://apis.io/apis/ukm/ukm-my-portal-website-wordpress-rest/) — The public WordPress REST API (wp-json) of the Universiti Kebangsaan Malaysia website at www.ukm.my/portal: the route index of the site's content management…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### JSON Schema (1)

The data models the API reads and writes.

- [UKM Web Content — WordPress page record](https://apis.io/schemas/ukm/ukm-wordpress-page/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Ukm Context](https://apis.io/jsonld/ukm/ukm-context/)

#### Examples (1)

Example requests and responses.

- [Ukm Portal Wp Json Root](https://apis.io/examples/ukm/ukm-portal-wp-json-root/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Ukm Authentication](https://apis.io/security/ukm/ukm-authentication/)
- [Ukm Domain Security](https://apis.io/security/ukm/ukm-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Ukm Plans Pricing](https://apis.io/plans/ukm/ukm-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Ukm Rate Limits](https://apis.io/rate-limits/ukm/ukm-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Ukm Finops](https://apis.io/finops/ukm/ukm-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.ukm.my/portal/)
- [API reference](https://www.ukm.my/portal/wp-json/)
- [Blog](https://www.ukm.my/beritaukm/)

## API Evangelist rating

**Kin Score 24.4** — emerging · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 62.5 |
| Contract quality | 38.3 |
| Contract governance | 15.2 |
| Operational transparency | 5.3 |
| Developer ergonomics | 26.2 |
| Access clarity | 5.3 |

**Agent readiness 24.5** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | na |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | na |
| Error Semantics | — |
| OpenAPI Examples | verified |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | na |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 16.7** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/ukm/](https://apis.io/providers/ukm/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Universiti Kebangsaan Malaysia: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/ukm/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
