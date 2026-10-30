# Nanjing University

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

Nanjing University (NJU, 南京大学), founded in 1902 in Nanjing, Jiangsu, is one of China's oldest research universities and a member of the C9 League. It publishes no developer portal, no API gateway, no API programme and no OpenAPI of its own, and this profile records that plainly. What it does operate — directly, on its own hosts, inside CERNET address space — is a genuine estate of institution-run machine-readable surfaces, almost all of it built and run by the university's e-Science Center: its own Shibboleth identity provider at idp.nju.edu.cn, registered in CARSI and republished to eduGAIN; a CAS single sign-on service whose ticket-validation endpoints answer the CAS 2.0 and 3.0 protocol to anonymous callers; a public open-source mirror at mirrors.nju.edu.cn serving JSON configuration endpoints; a GitLab instance at git.nju.edu.cn whose REST API v4 the mirror site itself consumes; a BookStack documentation service at doc.nju.edu.cn that publishes a complete 79-endpoint REST API reference publicly and gates the API on an NJU token; and Seafile, SeaTable and Vaultwarden deployments that answer unauthenticated service-discovery JSON. None of this is an API product, none of it is registerable by an outsider, and the contracts behind the service deployments are the upstream products', not NJU's engineering — so no vendor specification is saved here under NJU's name. The June 2026 profile of this institution saw none of it and recorded only a login page.

**Areas:** University · Higher Education · Education · China · C9 League · Research · Identity Federation · Authentication · SSO · Research Computing · Open Source Mirror · Version Control

## Nanjing University on APIs.io

Everything profiled for Nanjing University is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/nanjing/](https://apis.io/providers/nanjing/)** — or go straight to one of the APIs or properties below.

### APIs (14)

- [Nanjing University Shibboleth Identity Provider (SAML 2.0 metadata)](https://apis.io/apis/nanjing/idp-shibboleth/) — Nanjing University's own Shibboleth Identity Provider. It publishes SAML 2.0 metadata at the canonical /idp/shibboleth location — an EntityDescriptor with…
- [Nanjing University CARSI / eduGAIN Federation Registration](https://apis.io/apis/nanjing/carsi-edugain/) — NJU's entry in CARSI (CERNET Authentication and Resource Sharing Infrastructure), China's national research and education identity federation, republished…
- [Nanjing University Unified Identity Authentication (CAS SSO)](https://apis.io/apis/nanjing/cas-sso/) — NJU's central single sign-on, a CAS deployment supporting password, verification-code, biometric and QR-code login. It is not a developer API and there is…
- [NJU Mirror (open-source software mirror)](https://apis.io/apis/nanjing/mirrors/) — The university's public open-source mirror, run by the NJU e-Science Center and open to anyone on the internet. Beyond the package trees themselves, the…
- [NJU e-Science Code Hosting (GitLab REST API v4)](https://apis.io/apis/nanjing/gitlab/) — An institution-operated GitLab instance for NJU staff and students. Its REST API v4 is real and in production — the university's own mirror site fetches…
- [NJU e-Science Document Service API](https://apis.io/apis/nanjing/doc-bookstack/) — The e-Science Center's documentation platform (a BookStack deployment) publishes a complete public REST API reference at /api/docs — 79 endpoints across…
- [NJU Box (南大云盘) — Seafile deployment](https://apis.io/apis/nanjing/box/) — The university's cloud storage service for staff and students, a self-hosted Seafile 13.0.25 instance branded "南大云盘 NJU Box". Service discovery is anonymous…
- [NJU Table (南大表格) — SeaTable deployment](https://apis.io/apis/nanjing/table/) — An institution-hosted SeaTable 6.1.9 enterprise-edition deployment offering collaborative tables to NJU users. /api2/ping/ and /server-info/ answer…
- [NJU Password Manager (Vaultwarden deployment)](https://apis.io/apis/nanjing/pass/) — A self-hosted Vaultwarden 2026.6.0 instance offering a Bitwarden-protocol password vault to NJU users. /alive returns a server timestamp and /api/config…
- [NJU e-Science High Performance Computing Center](https://apis.io/apis/nanjing/hpc/) — Nanjing University's supercomputing service, operated by the e-Science Center under the Collaborative Innovation Center of Advanced Microstructures. It…
- [NJU Intelligent Assistant Platform (小蓝鲸)](https://apis.io/apis/nanjing/chat-assistant/) — "小蓝鲸" — the university's own AI assistant platform for NJU users, a single-page application backed by an astron-agent deployment with Casdoor as its…
- [Nanjing University Library Catalog (OPAC)](https://apis.io/apis/nanjing/opac/) — The library's catalog host. It is live but restricted to the campus network: every route, including an OAI-PMH probe, returns HTTP 403 with the body…
- [Nanjing University in the Research Organization Registry (ROR)](https://apis.io/apis/nanjing/ror/) — Nanjing University's registration in ROR, the open registry of research organizations: ROR ID 01rxvg760, domain nju.edu.cn, established 1902, with…
- [Nanjing University in the Crossref Open Funder Registry](https://apis.io/apis/nanjing/crossref-funder/) — Nanjing University's entry in the Crossref Open Funder Registry as funder 501100008048, with 3,401 works recording it as a funder and two descendant funder…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Nanjing Context](https://apis.io/jsonld/nanjing/nanjing-context/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Nanjing Authentication](https://apis.io/security/nanjing/nanjing-authentication/)
- [Nanjing Domain Security](https://apis.io/security/nanjing/nanjing-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Nanjing Plans Pricing](https://apis.io/plans/nanjing/nanjing-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Nanjing Rate Limits](https://apis.io/rate-limits/nanjing/nanjing-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Nanjing Finops](https://apis.io/finops/nanjing/nanjing-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.nju.edu.cn/en/)
- [Documentation](https://doc.nju.edu.cn/)
- [API reference](https://doc.nju.edu.cn/api/docs)
- [Support](https://itsc.nju.edu.cn/)
- [GitHub](https://github.com/MCG-NJU)

## API Evangelist rating

**Kin Score 24.7** — emerging · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 71.4 |
| Contract quality | 17.3 |
| Contract governance | 0.0 |
| Operational transparency | 7.9 |
| Developer ergonomics | 33.3 |
| Access clarity | 28.9 |

**Agent readiness 3.1** — human-only

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | — |
| Agentic Access | — |
| Reversibility Documented | — |
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

**Regulatory alignment 16.7** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/nanjing/](https://apis.io/providers/nanjing/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Nanjing University: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/nanjing/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
