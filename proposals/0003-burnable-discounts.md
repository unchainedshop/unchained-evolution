# Burnable Discounts

* Proposal: [SE-0003](0003-burnable-discounts.md)
* Authors: @pozylon
* Status: **Draft**
* Breaking: No

## Introduction

One Time burnable discounts

## Motivation

Currently a discount code in unchained cannot be dynamic. It is possible to make it kind of "one-time" though through discount code which takes into account:
- user tags
- locale
- product tags

But in general, a discount code could be used multiple times and does not get "burned".

## Proposed solution

Solve through a blockchain-based discounts system, implement bridges to systems like:
- https://www.gatcoin.io

## Detailed design

Lets a user generate one time discount codes in the admin panel which he/she then can download and use in any kind of way (printed, ...).
If a discount is used by a consumer, the discount code will get voided on order submission and it's guaranteed that it's not possible to use it a second time.

## Alternatives considered

* Stored tokens in MongoDB
* Just expose an API for plugins
