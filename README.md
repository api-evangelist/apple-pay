# Apple Pay (apple-pay)

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
