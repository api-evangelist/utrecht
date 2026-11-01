# Utrecht University

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

Utrecht University (Universiteit Utrecht) is a public research university in Utrecht, Netherlands, founded in 1636 and a member of the League of European Research Universities. It is one of the few universities in this catalog whose largest machine-readable surface is its OWN engineering rather than a vendor's: Utrecht authors and operates Yoda, a GPL-3.0 iRODS-based research data management platform (github.com/UtrechtUniversity/yoda-ruleset), and runs it in production at portal.yoda.uu.nl. The Yoda HTTP API is real but not open — every call redirects to SolisID login unless it carries a session cookie or a Yoda data access token — so the OpenAPIs in this repo describe a live institution-operated API that no anonymous client can call. Alongside it the University Library runs a DSpace 9.0 institutional repository whose REST API and OAI-PMH interface are both openly readable at dspace.library.uu.nl, and IT Services operates a SAML 2.0 identity provider registered in the SURFconext federation. The research information system is NOT Utrecht's: research-portal.uu.nl is an Elsevier Pure tenancy (uu.elsevierpure.com), recorded here as a tenant relationship and not as Utrecht's contract. There is no central developer portal, no api.uu.nl, no public course-catalog or campus API, and no published API terms or rate limits; OSIRIS, the student administration system, returns 403 to unauthenticated clients.

**Areas:** Education · Higher Education · University · Netherlands · Europe · Research Data · Research Data Management · Institutional Repository · Identity Federation · OAI-PMH · Open Access · Open Science

## Utrecht University on APIs.io

Everything profiled for Utrecht University is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/utrecht/](https://apis.io/providers/utrecht/)** — or go straight to one of the APIs or properties below.

### APIs (24)

- [Utrecht University Repository OAI-PMH](https://apis.io/apis/utrecht/repository-oai/) — OAI-PMH 2.0 metadata harvesting interface for the Utrecht University Library institutional repository. Verified live 2026-08-30 on DSpace 9.0: Identify,…
- [Utrecht University Admin API](https://apis.io/apis/utrecht/utrecht-admin-api/) — The admin API from Utrecht University — 1 operation(s) for admin.
- [Utrecht University Browse API](https://apis.io/apis/utrecht/utrecht-browse-api/) — The browse API from Utrecht University — 4 operation(s) for browse.
- [Utrecht University Data Access Token API](https://apis.io/apis/utrecht/utrecht-data-access-token-api/) — The data_access_token API from Utrecht University — 4 operation(s) for data_access_token.
- [Utrecht University Datarequest API](https://apis.io/apis/utrecht/utrecht-datarequest-api/) — The datarequest API from Utrecht University — 34 operation(s) for datarequest.
- [Utrecht University Folder API](https://apis.io/apis/utrecht/utrecht-folder-api/) — The folder API from Utrecht University — 7 operation(s) for folder.
- [Utrecht University Groups API](https://apis.io/apis/utrecht/utrecht-groups-api/) — The groups API from Utrecht University — 15 operation(s) for groups.
- [Utrecht University Meta API](https://apis.io/apis/utrecht/utrecht-meta-api/) — The meta API from Utrecht University — 2 operation(s) for meta.
- [Utrecht University Meta Form API](https://apis.io/apis/utrecht/utrecht-meta-form-api/) — The meta_form API from Utrecht University — 2 operation(s) for meta_form.
- [Utrecht University Notifications API](https://apis.io/apis/utrecht/utrecht-notifications-api/) — The notifications API from Utrecht University — 3 operation(s) for notifications.
- [Utrecht University Provenance API](https://apis.io/apis/utrecht/utrecht-provenance-api/) — The provenance API from Utrecht University — 1 operation(s) for provenance.
- [Utrecht University Publication Troubleshoot API](https://apis.io/apis/utrecht/utrecht-publication-troubleshoot-api/) — The publication_troubleshoot API from Utrecht University — 1 operation(s) for publication_troubleshoot.
- [Utrecht University Research API](https://apis.io/apis/utrecht/utrecht-research-api/) — The research API from Utrecht University — 13 operation(s) for research.
- [Utrecht University Revisions API](https://apis.io/apis/utrecht/utrecht-revisions-api/) — The revisions API from Utrecht University — 3 operation(s) for revisions.
- [Utrecht University Schema API](https://apis.io/apis/utrecht/utrecht-schema-api/) — The schema API from Utrecht University — 1 operation(s) for schema.
- [Utrecht University Schema Transformation API](https://apis.io/apis/utrecht/utrecht-schema-transformation-api/) — The schema_transformation API from Utrecht University — 1 operation(s) for schema_transformation.
- [Utrecht University Settings API](https://apis.io/apis/utrecht/utrecht-settings-api/) — The settings API from Utrecht University — 2 operation(s) for settings.
- [Utrecht University Stats API](https://apis.io/apis/utrecht/utrecht-stats-api/) — The stats API from Utrecht University — 4 operation(s) for stats.
- [Utrecht University Vault API](https://apis.io/apis/utrecht/utrecht-vault-api/) — The vault API from Utrecht University — 16 operation(s) for vault.
- [Utrecht University Vault Archive API](https://apis.io/apis/utrecht/utrecht-vault-archive-api/) — The vault_archive API from Utrecht University — 3 operation(s) for vault_archive.
- [Utrecht University Vault Deaccession API](https://apis.io/apis/utrecht/utrecht-vault-deaccession-api/) — The vault_deaccession API from Utrecht University — 4 operation(s) for vault_deaccession.
- [Utrecht University Repository REST API](https://apis.io/apis/utrecht/repository-rest/) — The DSpace 9.0 HAL/JSON REST API behind the Utrecht University Repository. Openly readable without a key: the root at /server/api enumerates ~60 link…
- [Utrecht University SAML 2.0 Identity Provider Metadata](https://apis.io/apis/utrecht/identity-federation/) — Signed SAML 2.0 EntityDescriptor for Utrecht University's identity provider, served as XML at a stable URL and carried in SURFconext's national federation…
- [Utrecht University Research Portal (Elsevier Pure tenancy)](https://apis.io/apis/utrecht/pure-research-portal/) — Utrecht University's current research information system and public research portal, running on Elsevier Pure. Two machine doors were probed on 2026-08-30:…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Utrecht Agentic Access](https://apis.io/agentic-access/utrecht/utrecht-agentic-access/)

#### JSON Schema (2)

The data models the API reads and writes.

- [Yoda API Error Result](https://apis.io/schemas/utrecht/utrecht-yoda-error/)
- [Yoda API Result](https://apis.io/schemas/utrecht/utrecht-yoda-result/)

#### JSON Structure (2)

Data models expressed in JSON Structure.

- [Utrecht Yoda Error Structure](https://apis.io/json-structure/utrecht/utrecht-yoda-error-structure/)
- [Utrecht Yoda Result Structure](https://apis.io/json-structure/utrecht/utrecht-yoda-result-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Utrecht Context](https://apis.io/jsonld/utrecht/utrecht-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Utrecht University Yoda API Vocabulary](https://apis.io/vocabularies/utrecht/utrecht-vocabulary/)

#### Examples (2)

Example requests and responses.

- [Utrecht Yoda Datarequest Submit Example](https://apis.io/examples/utrecht/utrecht-yoda-datarequest-submit-example/)
- [Utrecht Yoda Folder Submit Example](https://apis.io/examples/utrecht/utrecht-yoda-folder-submit-example/)

#### Collections (20)

Postman and Open Collection request collections.

- [Yoda core admin API](https://apis.io/collections/utrecht/open-utrecht-admin-api/)
- [Yoda core admin browse API](https://apis.io/collections/utrecht/open-utrecht-browse-api/)
- [Yoda core admin data_access_token API](https://apis.io/collections/utrecht/open-utrecht-data-access-token-api/)
- [Yoda core admin datarequest API](https://apis.io/collections/utrecht/open-utrecht-datarequest-api/)
- [Yoda core admin folder API](https://apis.io/collections/utrecht/open-utrecht-folder-api/)
- [Yoda core admin groups API](https://apis.io/collections/utrecht/open-utrecht-groups-api/)
- [Yoda core admin meta API](https://apis.io/collections/utrecht/open-utrecht-meta-api/)
- [Yoda core admin meta_form API](https://apis.io/collections/utrecht/open-utrecht-meta-form-api/)
- [Yoda core admin notifications API](https://apis.io/collections/utrecht/open-utrecht-notifications-api/)
- [Yoda core admin provenance API](https://apis.io/collections/utrecht/open-utrecht-provenance-api/)
- [Yoda core admin publication_troubleshoot API](https://apis.io/collections/utrecht/open-utrecht-publication-troubleshoot-api/)
- [Yoda core admin research API](https://apis.io/collections/utrecht/open-utrecht-research-api/)
- [Yoda core admin revisions API](https://apis.io/collections/utrecht/open-utrecht-revisions-api/)
- [Yoda core admin schema API](https://apis.io/collections/utrecht/open-utrecht-schema-api/)
- [Yoda core admin schema_transformation API](https://apis.io/collections/utrecht/open-utrecht-schema-transformation-api/)
- [Yoda core admin settings API](https://apis.io/collections/utrecht/open-utrecht-settings-api/)
- [Yoda core admin stats API](https://apis.io/collections/utrecht/open-utrecht-stats-api/)
- [Yoda core admin vault API](https://apis.io/collections/utrecht/open-utrecht-vault-api/)
- [Yoda core admin vault_archive API](https://apis.io/collections/utrecht/open-utrecht-vault-archive-api/)
- [Yoda core admin vault_deaccession API](https://apis.io/collections/utrecht/open-utrecht-vault-deaccession-api/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [Utrecht University — jsonschema rules](https://apis.io/rules/utrecht/utrecht-jsonschema-spectral-rules/)
- [Utrecht University API Rules](https://apis.io/rules/utrecht/utrecht-rules/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Utrecht Authentication](https://apis.io/security/utrecht/utrecht-authentication/)
- [Utrecht Domain Security](https://apis.io/security/utrecht/utrecht-domain-security/)
- [Utrecht Vulnerability Disclosure](https://apis.io/security/utrecht/utrecht-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Utrecht Plans Pricing](https://apis.io/plans/utrecht/utrecht-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Utrecht Rate Limits](https://apis.io/rate-limits/utrecht/utrecht-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Utrecht Finops](https://apis.io/finops/utrecht/utrecht-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.uu.nl/en)
- [Documentation](https://utrechtuniversity.github.io/yoda/)
- [API reference](https://dspace.library.uu.nl/server/api)
- [Support](https://www.uu.nl/en/contact)
- [Blog](https://www.uu.nl/en/organisation/news)
- [Terms of service](https://www.uu.nl/en/disclaimer)
- [Privacy policy](https://www.uu.nl/en/privacy)

## API Evangelist rating

**Kin Score 39.7** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 66.1 |
| Contract quality | 52.9 |
| Contract governance | 9.8 |
| Operational transparency | 21.1 |
| Developer ergonomics | 35.7 |
| Access clarity | 26.3 |

**Agent readiness 20.3** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | documented (partial credit) |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | mostly (partial credit) |

**Regulatory alignment 30.4** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/utrecht/](https://apis.io/providers/utrecht/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Utrecht University: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/utrecht/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
