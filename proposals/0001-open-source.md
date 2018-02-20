# Untangle to Open Source

* Proposal: [SE-0001][1]
* Authors: @pozylon @fliptation
* Status: **Awaiting Implementation**
* Breaking: Yes

This proposal mixed all remaining tasks together for a first v1.0 OSS release.
Removing the chains from customer projects and implement missing mandatory plugins.

**Missing features**:
- [x] Customizable Mail Templates
- [x] Bitcoin Payment Plugin
- [x] Ethereum Payment Plugin
- [ ] Stellar Payment Plugin
- [ ] "Token Distribution" Delivery Plugin (ICO)
- [ ] [Cart Sanity Check & Safe Migration](https://github.com/xecutors/unchained/issues/27)

**Required refactorings**:
- [x] Delivery Plugin System
- [x] Pricing Plugin System
- [x] Discount Plugin System
- [x] Payment Plugin System
- [x] Messaging Plugin System
- [x] Document Plugin System
- [x] Plugins as reusable Package
- [x] GraphQL API as reusable Package
- [x] [Whole engine as reusable Package](https://github.com/xecutors/unchained/issues/26)
- [x] [Stock Plugins](https://github.com/xecutors/unchained/issues/21)
- [ ] [Address schema customization (i18n)](https://github.com/xecutors/unchained/issues/14)
- [ ] [GraphQL Scheme 1.0 (Pointers, Edges, Response Types missing)](https://github.com/xecutors/unchained/issues/12)
- [ ] [Tests](https://github.com/xecutors/unchained/issues/3)

**Other**:
- [x] [Blog setup](https://github.com/xecutors/unchained/issues/17)

[1]:	0001-open-source.md