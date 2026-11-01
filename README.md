# University of Campinas

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

The University of Campinas (Universidade Estadual de Campinas, Unicamp) is a public research university in Campinas, Sao Paulo, Brazil, and one of Latin America's largest producers of research output. It publishes no central developer portal and no public API documentation, but it does operate more machine-readable surface than that absence suggests, and all of it sits on its own registrable domain: REDU, a self-hosted Dataverse 6.2 research data repository with a live Native/Search API and an OAI-PMH endpoint over 2,149 datasets; the EDAT data platform, whose Kong gateway at api.dados.unicamp.br serves at least one publicly callable JSON endpoint and gates the rest behind Unicamp's own Keycloak realm with full OIDC discovery; per-journal OAI-PMH across the SBU journal portal; and a Shibboleth identity provider registered in CAFe, Brazil's academic identity federation. Two further gateways are live but closed - the registrar API at api.dac.unicamp.br (403 on every path) and an institutional Sensedia gateway at api.unicamp.br (routing but no public route). Unicamp is also a DataCite provider in its own right and a Crossref member. Nothing here is documented for third-party developers; the contracts in this repo were reconstructed by probe, not published by the university.

**Areas:** Education · Higher Education · University · Public Research University · Brazil · Latin America · Research Data · Open Data · Research Repository · Identity Federation · OAI-PMH · Dataverse

## University of Campinas on APIs.io

Everything profiled for University of Campinas is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/unicamp/](https://apis.io/providers/unicamp/)** — or go straight to one of the APIs or properties below.

### APIs (12)

- [REDU Dataverse Native & Search API](https://apis.io/apis/unicamp/redu-dataverse-api/) — REDU (Repositorio de Dados de Pesquisa da Unicamp) is Unicamp's institutional research data repository, self-hosted on the open-source Dataverse platform at…
- [REDU OAI-PMH Metadata Endpoint](https://apis.io/apis/unicamp/redu-oai-pmh/) — OAI-PMH 2.0 metadata harvesting endpoint for REDU, on Unicamp's own host. Verified live 2026-09-01: verb=Identify returns 200 for repository "Repositorio de…
- [EDAT Keycloak OpenID Connect Provider](https://apis.io/apis/unicamp/edat-keycloak-oidc/) — Unicamp-operated Keycloak authorization server (realm `edat`) that issues the credentials for the EDAT data platform. Verified live 2026-09-01: the OIDC…
- [Unicamp Shibboleth Identity Provider (CAFe)](https://apis.io/apis/unicamp/cafe-shibboleth-idp/) — Unicamp's own SAML 2.0 / Shibboleth identity provider, entityID https://cafe.unicamp.br/idp/shibboleth, registered in CAFe - RNP's Brazilian academic…
- [SBU Journal Portal OAI-PMH Endpoints](https://apis.io/apis/unicamp/sbu-periodicos-oai/) — Unicamp's library system (SBU) self-hosts the Portal de Periodicos Eletronicos Cientificos on Open Journal Systems 3.4.0.9 at periodicos.sbu.unicamp.br,…
- [DAC Registrar API (closed)](https://apis.io/apis/unicamp/dac-registrar-api/) — API host of the Diretoria Academica (DAC), Unicamp's registrar, which runs the course catalogs, enrollment and academic records. Resolves to…
- [Institutional API Gateway (api.unicamp.br)](https://apis.io/apis/unicamp/institutional-api-gateway/) — Unicamp's central API gateway. The hostname is Unicamp's; the gateway platform is Sensedia (api.unicamp.br CNAMEs to…
- [DataCite Membership and DOI Registration](https://apis.io/apis/unicamp/datacite-membership/) — Unicamp is a DataCite provider (member) in its own right, not merely a client of one. Verified 2026-09-01: https://api.datacite.org/providers/unicamp…
- [Crossref Membership](https://apis.io/apis/unicamp/crossref-membership/) — Unicamp is Crossref member 27633, "Universidade Estadual de Campinas", registering DOIs for its SBU journal portal and other scholarly output. Verified…
- [ROR Organization Registration](https://apis.io/apis/unicamp/ror-registration/) — Unicamp is registered in the Research Organization Registry as https://ror.org/04wffgt70, with domain unicamp.br, established 1966, and cross-references to…
- [University of Campinas Authorization API](https://apis.io/apis/unicamp/unicamp-authorization-api/) — Role and permission metadata backing the EDAT Superset dashboards.
- [University of Campinas Support API](https://apis.io/apis/unicamp/unicamp-support-api/) — Support desk system registry.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Unicamp Context](https://apis.io/jsonld/unicamp/unicamp-context/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Unicamp Domain Security](https://apis.io/security/unicamp/unicamp-domain-security/)
- [Unicamp Edat Oidc Authentication](https://apis.io/security/unicamp/unicamp-edat-oidc-authentication/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Unicamp Edat Oidc Scopes](https://apis.io/scopes/unicamp/unicamp-edat-oidc-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Unicamp Plans Pricing](https://apis.io/plans/unicamp/unicamp-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Unicamp Rate Limits](https://apis.io/rate-limits/unicamp/unicamp-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Unicamp Finops](https://apis.io/finops/unicamp/unicamp-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.unicamp.br/)
- [Support](https://www.dados.unicamp.br/fale-com-o-edat/)
- [Privacy policy](https://privacidade.dados.unicamp.br/politica-de-privacidade/)

## API Evangelist rating

**Kin Score 37.1** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 66.1 |
| Contract quality | 54.7 |
| Contract governance | 18.2 |
| Operational transparency | 5.3 |
| Developer ergonomics | 26.2 |
| Access clarity | 28.9 |

**Agent readiness 24.5** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | na |
| MCP Server | — |
| Auth Clarity | negotiable (partial credit) |
| Idempotency | na |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | na |
| Delegated Identity | documented (partial credit) |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 38.2** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/unicamp/](https://apis.io/providers/unicamp/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for University of Campinas: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/unicamp/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
