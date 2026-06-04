# Macquarie University (macquarie)

Macquarie University is a public research university in Sydney, Australia, ranked #133 in the QS World University Rankings 2025. Its public, developer-relevant API footprint centers on research-data and library infrastructure rather than a single branded developer portal. The Research Data Repository runs on Figshare for Institutions (public Figshare REST API v2 + OAI-PMH), and the University Library publishes open-source Alma tooling on GitHub. Institutional SSO is provided via a Shibboleth/SAML identity provider.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/macquarie/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=macquarie-api-evangelist&utm_content=repo

## Type

- Index / Consumer / 3rd-Party

## Tags

- Education
- Higher Education
- University
- Research Data
- Library
- Australia

## APIs

- **Macquarie University Research Data Repository (Figshare API)** — Public datasets, theses, and research outputs from the Figshare-backed RDR, exposed via the public Figshare REST API v2 (DOI prefix 10.25949). Docs: https://docs.figshare.com/ · Portal: https://figshare.mq.edu.au/
- **Macquarie University Research Data Repository (OAI-PMH)** — Standards-based metadata harvesting of RDR content via the Figshare OAI-PMH endpoint (`https://api.figshare.com/v2/oai`). Docs: https://docs.figshare.com/
- **Macquarie University Library Open-Source Tooling** — Public Alma-integration utilities maintained by the Library on GitHub. GitHub: https://github.com/mqlibrary · Alma developer docs: https://developers.exlibrisgroup.com/alma/

## Plans

- [plans/macquarie-plans-pricing.yml](plans/macquarie-plans-pricing.yml)

## Rate Limits

- [rate-limits/macquarie-rate-limits.yml](rate-limits/macquarie-rate-limits.yml)

## FinOps

- [finops/macquarie-finops.yml](finops/macquarie-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.mq.edu.au/
- GitHub (institution): https://github.com/macquarie-university
- GitHub (library): https://github.com/mqlibrary
- LinkedIn: https://www.linkedin.com/school/macquarie-university/
- Authentication (Shibboleth/SAML IdP): https://idp.mq.edu.au/idp/shibboleth
- Plans: plans/macquarie-plans-pricing.yml
- Rate Limits: rate-limits/macquarie-rate-limits.yml
- FinOps: finops/macquarie-finops.yml
- Review: review.yml

## Notes

All endpoints in this profile were probed during the 2026-06-03 review; statuses are recorded in `review.yml`. No Macquarie-branded API endpoints were fabricated. The Figshare REST API v2 and OAI-PMH endpoints were verified to return live Macquarie content. The official `macquarie-university` GitHub org exists but has no public repositories. **Macquarie Bank** is a separate financial institution with its own developer portal (developer.macquariebank.io) and is intentionally excluded from this university profile. No dedicated Macquarie University developer portal, open-data platform, or public status page was found (`developer.mq.edu.au`, `data.mq.edu.au`, `status.mq.edu.au` do not resolve).

## Maintainers

- Kin Lane — kin@apievangelist.com
