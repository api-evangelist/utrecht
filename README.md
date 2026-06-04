# Utrecht University (utrecht)

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
