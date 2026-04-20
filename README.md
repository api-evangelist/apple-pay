# Apple Pay (apple-pay)
Apple Pay enables secure, frictionless payments in apps and on the web using the payment cards stored in users' Apple Wallet. It supports Touch ID, Face ID, and Apple Watch authentication for both in-person and online payments. Apple Pay is available on iOS, watchOS, macOS, and via Safari on the web through the Apple Pay JS API, with a PassKit native framework for iOS/watchOS app integration.

**URL:** [Visit APIs.json URL](https://developer.apple.com/apple-pay/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Apple, Contactless Payments, Digital Wallet, E-Commerce, Mobile Payments, Payments

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-04-19

## APIs

### Apple Pay JS API
Server-side REST API for Apple Pay on the Web, enabling merchants to validate their identity with Apple and obtain payment sessions used by the ApplePaySession JavaScript API in Safari.

**Human URL:** [https://developer.apple.com/documentation/apple_pay_on_the_web](https://developer.apple.com/documentation/apple_pay_on_the_web)

#### Tags:

 - Javascript, Safari, Web Payments

#### Properties

- [Documentation](https://developer.apple.com/documentation/apple_pay_on_the_web)
- [GettingStarted](https://developer.apple.com/apple-pay/implementation/)
- [APIReference](https://developer.apple.com/documentation/apple_pay_on_the_web/applepaypaymentrequest)
- [Sandbox](https://developer.apple.com/apple-pay/sandbox-testing/)
- [OpenAPI](openapi/apple-pay-js-openapi.yml)
- [JSONSchema - Payment Request Schema](json-schema/apple-pay-payment-request-schema.json)

### PassKit Framework (Apple Pay)
Native iOS, watchOS, and macOS framework for integrating Apple Pay into mobile and desktop applications.

**Human URL:** [https://developer.apple.com/documentation/passkit](https://developer.apple.com/documentation/passkit)

#### Tags:

 - iOS, Mobile, Native, Swift

#### Properties

- [Documentation](https://developer.apple.com/documentation/passkit/apple_pay)
- [APIReference](https://developer.apple.com/documentation/passkit/pkpaymentrequest)
- [CodeExamples - Sample Code](https://developer.apple.com/documentation/passkit/apple_pay/offering_apple_pay)
- [YouTube](https://developer.apple.com/videos/frameworks/wallet-and-apple-pay)

### Apple Pay Payment Token API
Server-side specification for processing and decrypting Apple Pay payment tokens received from client applications.

**Human URL:** [https://developer.apple.com/documentation/passkit/apple_pay/payment_token_format_reference](https://developer.apple.com/documentation/passkit/apple_pay/payment_token_format_reference)

#### Tags:

 - Encryption, Payment Processing, Server-Side

#### Properties

- [Documentation](https://developer.apple.com/documentation/passkit/apple_pay/payment_token_format_reference)
- [OpenAPI](openapi/apple-pay-payment-token-openapi.yml)
- [JSONSchema - Payment Token Schema](json-schema/apple-pay-payment-token-schema.json)

## Common Properties

- [Portal](https://developer.apple.com/account/)
- [Support](https://developer.apple.com/support/apple-pay/)
- [TermsOfService](https://developer.apple.com/apple-pay/acceptable-use-guidelines/)
- [GettingStarted](https://developer.apple.com/apple-pay/get-started/)
- [Branding](https://developer.apple.com/apple-pay/marketing/)
- [StatusPage](https://developer.apple.com/system-status/)

## Features

| Name | Description |
|------|-------------|
| Touch ID and Face ID Authentication | Users authorize payments using biometric authentication on Apple devices |
| In-App Payments | Native iOS and watchOS integration via PassKit framework |
| Web Payments | Safari-based Apple Pay checkout via the ApplePaySession JavaScript API |
| Apple Watch Support | Contactless payments from Apple Watch without needing iPhone |
| Multiple Card Networks | Supports Visa, Mastercard, Amex, Discover, JCB, UnionPay, and more |
| Merchant Domain Verification | Domain verification ensures only registered merchants can use Apple Pay |
| Recurring Payments | Subscription and automatic payment support via automatic payment requests |
| Deferred Payments | Support for deferred billing like hotel deposits and pre-orders |

## Use Cases

| Name | Description |
|------|-------------|
| E-Commerce Checkout | One-tap checkout on web and mobile using saved payment cards |
| In-App Purchases | Native iOS app purchases with Face ID or Touch ID authentication |
| Subscription Billing | Setting up recurring subscription payments authorized by the user |
| Contactless In-Store Payments | Tap-to-pay at point-of-sale terminals using iPhone or Apple Watch |
| Transit Payments | Paying for transit and transportation with Express Mode |

## Integrations

| Name | Description |
|------|-------------|
| Stripe | Stripe Elements and Stripe.js support Apple Pay via the Payment Request Button |
| Braintree | PayPal's Braintree SDK provides Apple Pay integration for iOS and web |
| Square | Square's iOS SDK supports Apple Pay for in-app and contactless payments |
| Adyen | Adyen payment platform supports Apple Pay for web and mobile checkout |
| Shopify | Shopify natively supports Apple Pay for accelerated checkout |
| WooCommerce | WooCommerce Stripe plugin enables Apple Pay on WordPress stores |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Apple Pay JS API](openapi/apple-pay-js-openapi.yml)
- [Apple Pay Payment Token API](openapi/apple-pay-payment-token-openapi.yml)

### JSON Schema

- [Payment Request Schema](json-schema/apple-pay-payment-request-schema.json)
- [Payment Token Schema](json-schema/apple-pay-payment-token-schema.json)

### JSON Structure

- [Payment Request Structure](json-structure/apple-pay-payment-request-structure.json)
- [Payment Token Structure](json-structure/apple-pay-payment-token-structure.json)

### JSON-LD

- [Apple Pay Context](json-ld/apple-pay-context.jsonld)

### Examples

- [Payment Request Example](examples/apple-pay-payment-request-example.json)
- [Payment Token Example](examples/apple-pay-payment-token-example.json)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Apple Pay JS API](capabilities/shared/apple-pay-js.yaml) — 2 operations for merchant validation and payment sessions

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Payment Processing](capabilities/payment-processing.yaml) | Apple Pay JS API | 2 | E-Commerce Developer, Payment Integration Engineer |

## Vocabulary

- [Apple Pay Vocabulary](vocabulary/apple-pay-vocabulary.yaml) — Unified taxonomy mapping 3 resources, 6 actions, 1 workflow, and 2 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Apple Pay Spectral Rules](rules/apple-pay-spectral-rules.yml) — 24 rules across 8 categories enforcing Apple Pay API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
