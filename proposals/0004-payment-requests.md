# Payment Requests API

* Proposal: [SE-0004](0004-payment-requests.md)
* Authors: @pozylon
* Status: **Draft**
* Breaking: Yes

## Introduction

Support "Express Checkout" like Payment provider setups that deliver address information pre-checkout:
- Payment Requests API
- Apple Pay
- PayPal Express (Payment Requests API)

## Motivation

* User experience is awesome
* TouchID payment support.

## Proposed solution

Implement natively:

* https://developers.google.com/web/fundamentals/payments/
* https://developer.apple.com/apple-pay/

## Detailed design

Required new special checkout flow:

1. Request Payment with amount and text
2. Get Delivery & Invoice Address + Contact information from external service.
3. "Do the regular checkout"

## Alternatives considered

- Implement through Stripe or other third party SDK's
