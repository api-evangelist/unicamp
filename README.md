# University of Campinas (unicamp)

The University of Campinas (Universidade Estadual de Campinas, Unicamp) is a public research university in Campinas, São Paulo, Brazil, ranked #232 in the QS World University Rankings 2025. This repository catalogs Unicamp's public developer/API footprint as an APIs.json profile for the API Evangelist network.

- APIs.json: <https://raw.githubusercontent.com/api-evangelist/unicamp/refs/heads/main/apis.yml>
- Run with Naftiko: <https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=unicamp-api-evangelist&utm_content=repo>

## Type

- Index / Consumer / 3rd-Party

## Tags

- Education
- Higher Education
- University
- Research Data
- Open Data
- Brazil

## APIs

- **REDU Dataverse Native & Search API** — Unicamp's research data repository on Dataverse 6.0; public Search and Native REST API. Docs: <https://guides.dataverse.org/en/6.0/api/> · Repository: <https://redu.unicamp.br/>
- **REDU OAI-PMH Metadata Endpoint** — OAI-PMH 2.0 metadata harvesting for REDU. Docs: <https://guides.dataverse.org/en/6.0/api/oai.html> · Endpoint: <https://redu.unicamp.br/oai>

## Plans

- [plans/unicamp-plans-pricing.yml](plans/unicamp-plans-pricing.yml)

## Rate Limits

- [rate-limits/unicamp-rate-limits.yml](rate-limits/unicamp-rate-limits.yml)

## FinOps

- [finops/unicamp-finops.yml](finops/unicamp-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: <https://www.unicamp.br/>
- LinkedIn: <https://br.linkedin.com/school/universidade-estadual-de-campinas/>
- Review: [review.yml](review.yml)

## Notes

- Verified live: the REDU Dataverse API (`/api/info/version` returns 6.0, Search API returns 1,957 datasets) and the REDU OAI-PMH `Identify` endpoint.
- Unicamp does not publish a unified public developer portal. The EDAT data office (dados.unicamp.br) delivers dashboards/panels through gated access with no documented API.
- The institutional repository (repositorio.unicamp.br, Sophia) did not expose a resolvable public OAI endpoint at probed paths.
- No official Unicamp GitHub organization was confirmed; `github.com/unicamp` is an empty personal account, and research-group orgs (e.g., unicamp-dl) are not institutional. GitHub is therefore omitted from common properties.
- No endpoints were fabricated; only confirmed URLs are listed.

## Maintainers

- Kin Lane — kin@apievangelist.com
