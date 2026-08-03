# Apple Pay (apple-pay)

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

Apple Pay enables secure, frictionless payments in apps and on the web using the payment cards stored in users' Apple Wallet. It supports Touch ID, Face ID, and Apple Watch authentication for both in-person and online payments. Apple Pay is available on iOS, watchOS, macOS, and via Safari on the web through the Apple Pay JS API, with a PassKit native framework for iOS/watchOS app integration.

**APIs.json:** [https://developer.apple.com/apple-pay/](https://developer.apple.com/apple-pay/)

## Tags

- Apple
- Contactless Payments
- Digital Wallet
- E-Commerce
- Mobile Payments
- Payments

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-05-19

## APIs

### Apple Pay JS API

Server-side REST API for Apple Pay on the Web, enabling merchants to validate their identity with Apple and obtain payment sessions used by the ApplePaySession JavaScript API in Safari. Supports Touch ID and Face ID for frictionless web checkout.

- **Human URL:** [https://developer.apple.com/documentation/apple_pay_on_the_web](https://developer.apple.com/documentation/apple_pay_on_the_web)
- **Base URL:** `https://apple-pay-gateway.apple.com`

#### Tags

- Javascript
- Safari
- Web Payments

#### Properties

- [Documentation](https://developer.apple.com/documentation/apple_pay_on_the_web)
- [Getting Started](https://developer.apple.com/apple-pay/implementation/)
- [API Reference](https://developer.apple.com/documentation/apple_pay_on_the_web/applepaypaymentrequest)
- [Sandbox](https://developer.apple.com/apple-pay/sandbox-testing/)
- [OpenAPI](openapi/apple-pay-js-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/apple-pay-js.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apple-pay-js.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/apple-pay-payment-request-schema.json) — [JSON Schema](https://json-schema.org/specification)

### PassKit Framework (Apple Pay)

Native iOS, watchOS, and macOS framework for integrating Apple Pay into mobile and desktop applications. Provides PKPaymentRequest and PKPaymentAuthorizationViewController for in-app Apple Pay checkout.

- **Human URL:** [https://developer.apple.com/documentation/passkit](https://developer.apple.com/documentation/passkit)
- **Base URL:** `Native Framework`

#### Tags

- iOS
- Mobile
- Native
- Swift

#### Properties

- [Documentation](https://developer.apple.com/documentation/passkit/apple_pay)
- [API Reference](https://developer.apple.com/documentation/passkit/pkpaymentrequest)
- [Code Examples](https://developer.apple.com/documentation/passkit/apple_pay/offering_apple_pay)
- [YouTube](https://developer.apple.com/videos/frameworks/wallet-and-apple-pay)
- [Postman Collection](collections/apple-pay-js.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apple-pay-js.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/apple-pay-payment-token.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apple-pay-payment-token.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Apple Pay Payment Token API

Server-side specification for processing and decrypting Apple Pay payment tokens received from client applications. Tokens use EC_v1 or RSA_v1 encryption and contain the payment authorization data for charge processing.

- **Human URL:** [https://developer.apple.com/documentation/passkit/apple_pay/payment_token_format_reference](https://developer.apple.com/documentation/passkit/apple_pay/payment_token_format_reference)
- **Base URL:** `Merchant Server`

#### Tags

- Encryption
- Payment Processing
- Server-Side

#### Properties

- [Documentation](https://developer.apple.com/documentation/passkit/apple_pay/payment_token_format_reference)
- [OpenAPI](openapi/apple-pay-payment-token-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/apple-pay-payment-token.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apple-pay-payment-token.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/apple-pay-payment-token-schema.json) — [JSON Schema](https://json-schema.org/specification)

## Common Properties

- [Portal](https://developer.apple.com/account/)
- [Support](https://developer.apple.com/support/apple-pay/)
- [Terms of Service](https://developer.apple.com/apple-pay/acceptable-use-guidelines/)
- [Getting Started](https://developer.apple.com/apple-pay/get-started/)
- [Branding](https://developer.apple.com/apple-pay/marketing/)
- [Status Page](https://developer.apple.com/system-status/)
- [JSON-LD](json-ld/apple-pay-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Spectral Rules](rules/apple-pay-spectral-rules.yml)
- [Vocabulary](vocabulary/apple-pay-vocabulary.yaml)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
