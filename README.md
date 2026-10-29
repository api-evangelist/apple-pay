# Apple Pay

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

Apple Pay enables secure, frictionless payments in apps and on the web using the payment cards stored in users' Apple Wallet. It supports Touch ID, Face ID, and Apple Watch authentication for both in-person and online payments. Apple Pay is available on iOS, watchOS, macOS, and via Safari on the web through the Apple Pay JS API, with a PassKit native framework for iOS/watchOS app integration.

**Areas:** Apple · Contactless Payments · Digital Wallet · E-Commerce · Mobile Payments · Payments

## Apple Pay on APIs.io

Everything profiled for Apple Pay is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/apple-pay/](https://apis.io/providers/apple-pay/)** — or go straight to one of the APIs or properties below.

### APIs (5)

- [PassKit Framework (Apple Pay)](https://apis.io/apis/apple-pay/passkit-framework-apple-pay/) — Native iOS, watchOS, and macOS framework for integrating Apple Pay into mobile and desktop applications. Provides PKPaymentRequest and…
- [Apple Pay Merchant Registration API](https://apis.io/apis/apple-pay/apple-pay-merchant-registration-api/) — Register and manage merchant domains for Apple Pay on the Web
- [Apple Pay Merchant Validation API](https://apis.io/apis/apple-pay/apple-pay-merchant-validation-api/) — Validate merchant identity and obtain payment sessions
- [Apple Pay Payment Processing API](https://apis.io/apis/apple-pay/apple-pay-payment-processing-api/) — Endpoints for receiving and processing Apple Pay payment tokens
- [Apple Pay Payment Status API](https://apis.io/apis/apple-pay/apple-pay-payment-status-api/) — Endpoints for checking payment transaction status

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Apple Pay Agentic Access](https://apis.io/agentic-access/apple-pay/apple-pay-agentic-access/)

#### JSON Schema (2)

The data models the API reads and writes.

- [Apple Pay Payment Request](https://apis.io/schemas/apple-pay/apple-pay-payment-request/)
- [Apple Pay Payment Token](https://apis.io/schemas/apple-pay/apple-pay-payment-token/)

#### JSON Structure (2)

Data models expressed in JSON Structure.

- [Apple Pay Payment Request Structure](https://apis.io/json-structure/apple-pay/apple-pay-payment-request-structure/)
- [Apple Pay Payment Token Structure](https://apis.io/json-structure/apple-pay/apple-pay-payment-token-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Apple Pay Context](https://apis.io/jsonld/apple-pay/apple-pay-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Apple Pay Vocabulary](https://apis.io/vocabularies/apple-pay/apple-pay-vocabulary/)

#### Examples (2)

Example requests and responses.

- [Apple Pay Payment Request Example](https://apis.io/examples/apple-pay/apple-pay-payment-request-example/)
- [Apple Pay Payment Token Example](https://apis.io/examples/apple-pay/apple-pay-payment-token-example/)

#### Collections (10)

Postman and Open Collection request collections.

- [Apple Pay JS API](https://apis.io/collections/apple-pay/open-apple-pay-js/)
- [Apple Pay JS Merchant Registration API](https://apis.io/collections/apple-pay/open-apple-pay-merchant-registration-api/)
- [Apple Pay JS Merchant Registration Merchant Validation API](https://apis.io/collections/apple-pay/open-apple-pay-merchant-validation-api/)
- [Apple Pay JS Merchant Registration Payment Processing API](https://apis.io/collections/apple-pay/open-apple-pay-payment-processing-api/)
- [Apple Pay JS Merchant Registration Payment Status API](https://apis.io/collections/apple-pay/open-apple-pay-payment-status-api/)
- [Apple Pay Payment Token API](https://apis.io/collections/apple-pay/open-apple-pay-payment-token/)
- [Apple Pay JS Merchant Registration API](https://apis.io/collections/apple-pay/postman-apple-pay-merchant-registration-api/)
- [Apple Pay JS Merchant Registration Merchant Validation API](https://apis.io/collections/apple-pay/postman-apple-pay-merchant-validation-api/)
- [Apple Pay JS Merchant Registration Payment Processing API](https://apis.io/collections/apple-pay/postman-apple-pay-payment-processing-api/)
- [Apple Pay JS Merchant Registration Payment Status API](https://apis.io/collections/apple-pay/postman-apple-pay-payment-status-api/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [Apple Pay — jsonschema rules](https://apis.io/rules/apple-pay/apple-pay-jsonschema-spectral-rules/)
- [Apple Pay API Rules](https://apis.io/rules/apple-pay/apple-pay-spectral-rules/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Apple Pay Authentication](https://apis.io/security/apple-pay/apple-pay-authentication/)
- [Apple Pay Domain Security](https://apis.io/security/apple-pay/apple-pay-domain-security/)
- [Apple Pay Vulnerability Disclosure](https://apis.io/security/apple-pay/apple-pay-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Apple Pay Plans Pricing](https://apis.io/plans/apple-pay/apple-pay-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Apple Pay Rate Limits](https://apis.io/rate-limits/apple-pay/apple-pay-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Apple Pay Finops](https://apis.io/finops/apple-pay/apple-pay-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.apple.com/)
- [Getting started](https://developer.apple.com/apple-pay/get-started/)
- [Support](https://developer.apple.com/support/apple-pay/)
- [Terms of service](https://developer.apple.com/apple-pay/acceptable-use-guidelines/)
- [Status](https://developer.apple.com/system-status/)

## API Evangelist rating

**Kin Score 44.3** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 73.2 |
| Contract quality | 64.6 |
| Contract governance | 27.3 |
| Operational transparency | 34.2 |
| Developer ergonomics | 63.1 |
| Access clarity | 5.3 |

**Agent readiness 31.1** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bound |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | documented (partial credit) |
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
| Operation Distinctiveness | distinct |

**Regulatory alignment 20.5** — Payments

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/apple-pay/](https://apis.io/providers/apple-pay/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Apple Pay: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/apple-pay/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
