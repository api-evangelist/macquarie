# Macquarie University (macquarie)

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

Macquarie University is a public research university in Sydney, Australia. Its programmable footprint is small, real, and almost entirely indirect. It operates no developer portal, no open-data platform and no central API programme. The one institution-operated, keyless, machine-readable API surface found is the **Macquarie University Research Portal OAI-PMH endpoint** at `research-management.mq.edu.au`, serving 114,062 publication records and a person registry over OAI-PMH 2.0 in five metadata formats with no authentication. Alongside it Macquarie runs a Shibboleth SAML identity provider registered in the Australian Access Federation, a self-hosted Moodle (iLearn) whose web services are credential-gated, and a public Library GitHub organisation whose code consumes Ex Libris Alma rather than exposing anything.

Everything else that looks like a Macquarie API is a vendor's contract running under Macquarie's name — Figshare, Elsevier Pure, CourseLoop, Ex Libris Primo. Those relationships are recorded here as tenant surfaces; the vendors' contracts are not.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/macquarie/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=macquarie-api-evangelist&utm_content=repo

## Type

- University / Public Research University / Index

## Tags

- University
- Higher Education
- Education
- Australia
- Research Data
- Research Repository
- Metadata Harvesting
- OAI-PMH
- Identity Federation
- Library
- Course Catalog

## Surfaces

Every surface carries an operator. `x-operator: institution` means Macquarie runs the thing; `tenant` means Macquarie's data on a vendor's platform, where the contract belongs to the vendor and is deliberately not held here.

**Institution-operated**

- **Macquarie University Research Portal OAI-PMH** (`https://research-management.mq.edu.au/ws/oai`) — keyless OAI-PMH 2.0. All six verbs execute anonymously; formats `oai_dc`, `mods`, `xmetadiss`, `nl_didl`, `qdc`; `publications:all` reports `completeListSize` 114,062. Described in [openapi/macquarie-research-portal-oai-pmh-openapi.yml](openapi/macquarie-research-portal-oai-pmh-openapi.yml), **derived from live probes** on 2026-08-30 — Macquarie publishes no OpenAPI for it.
- **Identity Provider (Shibboleth / SAML 2.0)** (`https://idp.mq.edu.au/idp/shibboleth`) — SAML metadata, registered in the Australian Access Federation as `urn:mace:federation.org.au:testfed:mq.edu.au`, asserting REFEDS R&S, the GEANT/REFEDS codes of conduct and SIRTFI.
- **iLearn (Moodle) Web Services** (`https://ilearn.mq.edu.au/webservice/rest/server.php`) — reachable, structured `invalidtoken` error, every function credential-gated. No LTI platform endpoint answers.
- **Library open-source tooling** (`https://github.com/mqlibrary`) — six public repos that *consume* Ex Libris Alma. None exposes an API.

**Tenant (vendor contract, not Macquarie's)**

- **Research Portal (Elsevier Pure)** — `researchers.mq.edu.au` / `research-management.mq.edu.au/ws/api`. The spec at `/ws/api/openapi.json` is Elsevier's: `info.title` "Pure API", `contact` `pure-support@elsevier.com`, version 5.33.3-3, 568 paths, relative `servers: /ws/api`.
- **Research Data Repository (Figshare)** — `figshare.mq.edu.au`, DOI prefix 10.25949 via DataCite `ARDCX.MQU`. API is Figshare's generic v2, shared with 14+ other institutions in this catalog.
- **Course Handbook (CourseLoop)** — `coursehandbook.mq.edu.au`, tenant `siteId: mq-prod-pres` on `api-ap-southeast-2.prod.courseloop.com`. Anonymous calls return 403.
- **Library MultiSearch (Ex Libris Primo)** — `multisearch.mq.edu.au`.

## Domain standards (education regime)

Confirmed with a fetched location: **oai-pmh**, **shibboleth**, **saml**, **datacite**. Checked and not found: **orcid**, **crossref**, **lti**, **scim**, **oneroster**, **ed-fi**, **caliper**, **qti**. See [conformance/macquarie-domain-standards.yml](conformance/macquarie-domain-standards.yml) for the evidence behind every one of them, including the negatives.

## Artifacts

- [openapi/macquarie-research-portal-oai-pmh-openapi.yml](openapi/macquarie-research-portal-oai-pmh-openapi.yml) · [openapi/_original/](openapi/_original/)
- [examples/macquarie-oai-pmh-examples.json](examples/macquarie-oai-pmh-examples.json) — verbatim captured responses
- [authentication/macquarie-authentication.yml](authentication/macquarie-authentication.yml) · [errors/macquarie-oai-pmh-errors.yml](errors/macquarie-oai-pmh-errors.yml)
- [conformance/macquarie-domain-standards.yml](conformance/macquarie-domain-standards.yml) · [lifecycle/macquarie-lifecycle.yml](lifecycle/macquarie-lifecycle.yml)
- [vocabulary/macquarie-oai-pmh-vocabulary.yml](vocabulary/macquarie-oai-pmh-vocabulary.yml) · [rules/macquarie-oai-pmh-spectral-rules.yml](rules/macquarie-oai-pmh-spectral-rules.yml)
- [plans/macquarie-plans-pricing.yml](plans/macquarie-plans-pricing.yml) · [rate-limits/macquarie-rate-limits.yml](rate-limits/macquarie-rate-limits.yml) · [finops/macquarie-finops.yml](finops/macquarie-finops.yml)
- [security/macquarie-domain-security.yml](security/macquarie-domain-security.yml) · [review.yml](review.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-08-30

## Common Properties

- Website: https://www.mq.edu.au/ (403 to non-browser clients — bot-filtered, not dead)
- GitHub (library): https://github.com/mqlibrary
- LinkedIn: https://www.linkedin.com/school/macquarie-university/
- Identity federation: https://idp.mq.edu.au/idp/shibboleth · https://md.aaf.edu.au/aaf-metadata.xml
- Research repository: https://researchers.mq.edu.au/ · https://figshare.mq.edu.au/
- Course catalog: https://coursehandbook.mq.edu.au/
- Library catalog: https://multisearch.mq.edu.au/
- AI policy: https://policies.mq.edu.au/document/view.php?id=394
- Privacy policy: https://policies.mq.edu.au/document/view.php?id=107
- Terms (Acceptable Use of IT Resources): https://policies.mq.edu.au/document/view.php?id=234

## Notes

**Attribution correction, 2026-08-30.** This profile was rebuilt under the API Evangelist university pipeline. The 2026-06-03 profile had saved a copy of the **generic Figshare API v2 contract** under Macquarie's slug (`info.title` "Figshare API (Macquarie University Research Data Repository)", `info.contact` "Figshare Support", `servers: https://api.figshare.com/v2`); `refine-openapis` split it into ten per-tag documents, and eleven `apis[]` entries plus schemas, structures, examples, rules, a vocabulary, a JSON-LD context, scopes, an authentication profile, an agentic-access card, capability edges and twenty-one collection documents were derived from it. All 47 files and 11 entries were removed. `api.figshare.com` is claimed by fourteen other institutions in this catalog.

The Figshare **relationship** was not deleted. `figshare.mq.edu.au` holds Macquarie's data under Macquarie's DOI prefix and survives as a tenant surface. Only the contract and its derivatives went.

No Macquarie-branded endpoint has been fabricated. Hosts that do not resolve: `api.mq.edu.au`, `developer.mq.edu.au`, `data.mq.edu.au`, `timetable.mq.edu.au`, `status.mq.edu.au`, `lib.mq.edu.au`. **Macquarie Bank** is a separate financial institution with its own developer portal (developer.macquariebank.io) and is intentionally excluded from this university profile.

## Maintainers

- Kin Lane — kin@apievangelist.com
