# Utrecht University (utrecht)

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

Utrecht University (Universiteit Utrecht) is a public research university in the Netherlands, ranked #105 in the QS World University Rankings 2025. Its public developer and API footprint centers on open research infrastructure — a DSpace institutional repository with OAI-PMH metadata harvesting, the open-source Yoda research data management platform, and a large public GitHub organization — rather than a single self-service API developer portal.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/utrecht/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=utrecht-api-evangelist&utm_content=repo

## Type

- Index / Consumer / 3rd-Party

## Tags

Education, Higher Education, University, Netherlands, Research Data, Open Access, Library, Open Source

## APIs

- **Utrecht University Repository OAI-PMH** — OAI-PMH metadata harvesting for the Library's DSpace institutional repository. Docs: https://www.uu.nl/en/university-library/utrecht-university-repository — Base URL: https://dspace.library.uu.nl/server/oai/request
- **Yoda Research Data Management Platform** — Open-source iRODS-based research data service (deposit, share, publish, preserve). Docs: https://utrechtuniversity.github.io/yoda/ — Source: https://github.com/UtrechtUniversity/yoda

## Plans

- [plans/utrecht-plans-pricing.yml](plans/utrecht-plans-pricing.yml)

## Rate Limits

- [rate-limits/utrecht-rate-limits.yml](rate-limits/utrecht-rate-limits.yml)

## FinOps

- [finops/utrecht-finops.yml](finops/utrecht-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.uu.nl/en
- GitHub: https://github.com/UtrechtUniversity
- LinkedIn: https://www.linkedin.com/school/utrecht-university/
- Repository: https://dspace.library.uu.nl/
- Review: [review.yml](review.yml)

## Notes

Findings reflect publicly verifiable resources only. The DSpace OAI-PMH endpoint was confirmed live (DSpace 9, valid OAI-PMH 2.0 XML). Yoda code and documentation are public, but live data access requires institutional SolisID/SSO credentials. The `catalog.data.uu.nl` host did not resolve during review and is not cataloged. No endpoints were fabricated; administrative/identity systems are gated and not openly documented as self-service APIs.

## Maintainers

- Kin Lane — kin@apievangelist.com
