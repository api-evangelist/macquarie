# Macquarie University

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

Macquarie University is a public research university in Sydney, Australia. Its programmable footprint is small, real, and almost entirely indirect: it operates no developer portal, no open-data platform, and no central API programme. The one institution-operated, keyless, machine-readable API surface found is the Macquarie University Research Portal OAI-PMH endpoint at research-management.mq.edu.au, which serves 114,062 publication records and a person registry over OAI-PMH 2.0 with five metadata formats and no authentication. Beyond it, Macquarie operates a Shibboleth SAML identity provider registered in the Australian Access Federation, a self-hosted Moodle (iLearn) whose web services are credential-gated, and a public library GitHub organisation whose code consumes Ex Libris Alma rather than exposing anything. Everything else that looks like a Macquarie API is a vendor's contract running under Macquarie's name — Figshare for the research data repository, Elsevier Pure for the research portal, CourseLoop for the course handbook, Ex Libris Primo for library discovery. Those relationships are recorded here as tenant surfaces; the vendors' contracts are not.

**Areas:** University · Higher Education · Education · Australia · Group of Eight Peer · Research Data · Research Repository · Metadata Harvesting · OAI-PMH · Identity Federation · Library · Course Catalog

## Macquarie University on APIs.io

Everything profiled for Macquarie University is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/macquarie/](https://apis.io/providers/macquarie/)** — or go straight to one of the APIs or properties below.

### APIs (8)

- [Macquarie University Identity Provider (Shibboleth / SAML 2.0)](https://apis.io/apis/macquarie/idp-shibboleth/) — Macquarie operates its own Shibboleth identity provider at idp.mq.edu.au, publishing SAML 2.0 metadata anonymously at /idp/shibboleth and registered in the…
- [Macquarie University iLearn (Moodle) Web Services](https://apis.io/apis/macquarie/ilearn-moodle-webservices/) — Macquarie self-hosts its learning management system as iLearn at ilearn.mq.edu.au and the Moodle web services REST endpoint answers publicly with a…
- [Macquarie University Library Open-Source Tooling](https://apis.io/apis/macquarie/library-alma-tools/) — The Macquarie University Library publishes six public repositories on GitHub as the mqlibrary organisation — an Alma toolkit (now archived),…
- [Macquarie University Research Portal (Elsevier Pure)](https://apis.io/apis/macquarie/research-portal-pure/) — Macquarie's research-information system is Elsevier Pure, tenanted on Macquarie hosts — researchers.mq.edu.au for the public portal and…
- [Macquarie University Research Data Repository (Figshare)](https://apis.io/apis/macquarie/rdr-figshare/) — The Macquarie University Research Data Repository is Figshare for Institutions, tenanted at figshare.mq.edu.au with DOI prefix 10.25949 minted through…
- [Macquarie University Course Handbook (CourseLoop)](https://apis.io/apis/macquarie/course-handbook-courseloop/) — The Macquarie course handbook runs on CourseLoop as tenant siteId mq-prod-pres, served at coursehandbook.mq.edu.au from a shared vendor API at…
- [Macquarie University Library MultiSearch (Ex Libris Primo)](https://apis.io/apis/macquarie/library-multisearch-primo/) — Library discovery for Macquarie runs on Ex Libris Primo at multisearch.mq.edu.au. The holdings are Macquarie's; Primo and the Alma platform beneath it are…
- [Macquarie University Harvesting API](https://apis.io/apis/macquarie/macquarie-harvesting-api/) — OAI-PMH 2.0 verbs for incremental metadata harvesting.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Vocabulary (1)

The provider's domain terms, defined.

- [Macquarie University Research Data Repository Vocabulary](https://apis.io/vocabularies/macquarie/macquarie-vocabulary/)

#### Examples (1)

Example requests and responses.

- [Macquarie Oai Pmh Examples](https://apis.io/examples/macquarie/macquarie-oai-pmh-examples/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Macquarie University — oai pmh rules](https://apis.io/rules/macquarie/macquarie-oai-pmh-spectral-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Macquarie Authentication](https://apis.io/security/macquarie/macquarie-authentication/)
- [Macquarie Domain Security](https://apis.io/security/macquarie/macquarie-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Macquarie Plans Pricing](https://apis.io/plans/macquarie/macquarie-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Macquarie Rate Limits](https://apis.io/rate-limits/macquarie/macquarie-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Macquarie Finops](https://apis.io/finops/macquarie/macquarie-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.mq.edu.au/)
- [Documentation](https://libguides.mq.edu.au/research_data_repository)
- [Support](https://policies.mq.edu.au/contact.php)
- [Terms of service](https://policies.mq.edu.au/document/view.php?id=234)
- [Privacy policy](https://policies.mq.edu.au/document/view.php?id=107)
- [GitHub](https://github.com/mqlibrary)

## API Evangelist rating

**Kin Score 33.5** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 57.1 |
| Contract quality | 48.5 |
| Contract governance | 26.5 |
| Operational transparency | 7.9 |
| Developer ergonomics | 26.2 |
| Access clarity | 26.3 |

**Agent readiness 20.1** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | na |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | na |
| Error Semantics | — |
| OpenAPI Examples | documented (partial credit) |
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

**Regulatory alignment 24.5** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/macquarie/](https://apis.io/providers/macquarie/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Macquarie University: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/macquarie/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
