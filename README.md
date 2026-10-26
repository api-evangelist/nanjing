# Nanjing University (nanjing)

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

Nanjing University (NJU, 南京大学), founded in 1902 in Nanjing, Jiangsu, is one of China's oldest research universities and a member of the C9 League. This repository is an APIs.json provider profile of NJU's publicly observable, machine-readable footprint.

NJU publishes **no developer portal, no API gateway, no API programme and no OpenAPI**. What it does operate — directly, on its own `nju.edu.cn` hosts inside CERNET address space, almost all of it run by the university's e-Science Center — is a genuine estate of institution-run machine-readable surfaces. Every entry below was probed live on 2026-09-01; see [review.yml](review.yml) for the full status table.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/nanjing/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=nanjing-api-evangelist&utm_content=repo

## Type

- Index
- Consumer
- 3rd-Party
- University · Public Research University

## Tags

University, Higher Education, Education, China, C9 League, Research, Identity Federation, Authentication, Single Sign-On, Research Computing, Open Source Mirror, Version Control, Library

## Surfaces

Every surface carries an operator: **institution** (NJU runs it), **federation** (a shared identity federation carrying NJU's own entity), or **registry** (an identifier registry NJU is registered in). No vendor's contract is saved under NJU's name.

| Surface | Operator | Status |
|---|---|---|
| **Shibboleth Identity Provider** — SAML 2.0 metadata at `idp.nju.edu.cn/idp/shibboleth` | institution | 200 `application/xml` |
| **CARSI / eduGAIN registration** — entity 671521, scope `nju.edu.cn`, first seen 2020-02-18 | federation | 200 |
| **CAS Single Sign-On** — `authserver.nju.edu.cn`, CAS 2.0/3.0 ticket validation in XML | institution | 200 |
| **NJU Mirror** — `mirrors.nju.edu.cn/configs/*.json`, unauthenticated JSON | institution | 200 |
| **e-Science GitLab** — `git.nju.edu.cn/api/v4`, REST API v4 | institution | live behind an Anubis bot challenge |
| **e-Science Document API** — `doc.nju.edu.cn/api`, 79 documented endpoints | institution | docs 200, API 401 (NJU token) |
| **NJU Box** — Seafile 13.0.25, `box.nju.edu.cn/api2` | institution | 200 |
| **NJU Table** — SeaTable 6.1.9, `table.nju.edu.cn` | institution | 200 |
| **Password manager** — Vaultwarden 2026.6.0, `pass.nju.edu.cn` | institution | 200 |
| **HPC / supercomputing** — `hpc.nju.edu.cn` | institution | 200, no public API |
| **小蓝鲸 AI assistant** — `chat.nju.edu.cn` | institution | 200, SPA shell only |
| **Library OPAC** — `opac.nju.edu.cn` | institution | 403, campus-network gated |
| **ROR** — `01rxvg760` | registry | 200 |
| **Crossref Open Funder Registry** — `501100008048` | registry | 200 |

## Identity Federation

- [identity-federation/nanjing-identity-federation.yml](identity-federation/nanjing-identity-federation.yml)
- [identity-federation/nanjing-idp-saml-metadata.xml](identity-federation/nanjing-idp-saml-metadata.xml) — archived verbatim from NJU's own host

## Conformance

- [conformance/nanjing-education-standards-conformance.yml](conformance/nanjing-education-standards-conformance.yml) — `shibboleth` and `saml` conformant; `oai-pmh`, `orcid`, `datacite`, `crossref`, `scim`, `lti`, `oneroster`, `ed-fi`, `caliper`, `qti` probed and not found

## Authentication

- [authentication/nanjing-authentication.yml](authentication/nanjing-authentication.yml)

## Plans

- [plans/nanjing-plans-pricing.yml](plans/nanjing-plans-pricing.yml)

## Rate Limits

- [rate-limits/nanjing-rate-limits.yml](rate-limits/nanjing-rate-limits.yml)

## FinOps

- [finops/nanjing-finops.yml](finops/nanjing-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-09-01

## Common Properties

- Website: https://www.nju.edu.cn/en/
- Documentation: https://doc.nju.edu.cn/
- API Reference: https://doc.nju.edu.cn/api/docs
- GitHub: https://github.com/MCG-NJU and https://github.com/nju-websoft (NJU research-group orgs; there is no central university API org)
- LinkedIn: https://www.linkedin.com/school/nanjing-university/
- Identity Federation: https://idp.nju.edu.cn/idp/shibboleth
- Research Computing: https://hpc.nju.edu.cn/zh/
- Library Catalog: https://lib.nju.edu.cn/
- AI Tooling: https://chat.nju.edu.cn/
- Support: https://itsc.nju.edu.cn/
- Authentication: https://authserver.nju.edu.cn/authserver/login

## Notes

This profile was assembled entirely from public probes; no credentials were used and no endpoints were fabricated.

**What is deliberately absent.** No vendor contract is saved under Nanjing University's name. The GitLab, BookStack, Seafile, SeaTable and Vaultwarden APIs are those products' engineering — NJU operates the deployments, and only the deployments are recorded. The Summon discovery instance the library still links (`nju.summon.serialssolutions.com`) returns 404 on every path and is not recorded as a live surface. NJU is not a Crossref member and not a DataCite client; the only Crossref member matching a "Nanjing University" query is Nanjing University of Aeronautics and Astronautics, a different institution, and it is not attributed here.

**Gated is not absent.** Three surfaces are live but closed to outside clients and are recorded as findings rather than gaps: the library OPAC returns 403 "请使用南大VPN访问!" on every route, `git.nju.edu.cn` answers non-browser clients with an Anubis proof-of-work challenge, and `data.nju.edu.cn` and `elearning.nju.edu.cn` return HTTP 483 WAF maintenance pages that could not be read from outside China. One host is a false lead worth naming: `api.nju.edu.cn` returns HTTP 200 and the body is the stock Apache Tomcat 8.5.98 welcome page.

**Supersedes the June 2026 profile,** which recorded only a CAS login page and the library website and concluded that no public API surface existed. That held for "API programme" and did not hold for "machine-readable surface". See [review.yml](review.yml).

## Maintainers

- Kin Lane — kin@apievangelist.com
