# unchained.shop Evolution

This repository tracks the ongoing evolution of the unchained shop. It contains:

* Platform State of the Union: A general overview of all the software components that are part of the platform
* Roadmap: Goals for upcoming unchained engine releases (this document)
* [Proposals / Feature Requests](proposals/proposals.md) for upcoming engine releases
* Software Architecture

## Roadmap

- [x] 2017.11 GoLive with first Customer [Freezyboy](https://www.freezyboy.com)
- [x] 2018.01 Landing Page
- [ ] 2018.02 Sketch out the big plan
- [ ] 2018.03 Whitelisting / Registration for Investors open
- [ ] 2018.03 Pre-ICO Distribution
- [ ] 2018.03 Hire Community, PR & Social Media Management Staff as well as test and documentation engineers.
- [ ] 2018.04 ICO (2018/04/2 - 2018/04/16)
- [ ] 2018.08 Open-Source release: Release of unchained engine 1.0 and admin UI 1.0. If we hit the hard-cap, we will release everything under the very permissive MIT license terms. Else we will be licensing the e-commerce platform under a stricter AGPLv3. After that day we will try to release new stable versions of unchained on a monthly rhythm and canary releases weekly.
- [ ] 2018.09 Hire more core engineers
- [ ] 2019.01 First Unchained Dev Conference in Zermatt, Switzerland.
- [ ] 2019.01 Presentation of our next-generation open-source business model
- [ ] 2019.03 Hire sales
- [ ] 2019.12 Break even

## Development major version:  unchained 1.0

Expected release date: Late 2018

### Primary Task: Open Source Readyness

The first version which will be publicly available. To do this we will have to unchain some major components from the reference implementation and move code which is customer-specific out of the base branch.

The following tasks are currently blocking the first OSS version of our product:

**Required features / improvements**:
- [ ] Customizable Mail Templates
- [x] Bitcoin Payment Plugin
- [x] Ethereum Payment Plugin
- [ ] Stellar Payment Plugin
- [ ] "Token Distribution" Delivery Plugin (ICO)
- [ ] Tests

**Core Package Refactorings needed**:
- [x] Delivery Plugin System
- [x] Warehousing Plugin System
- [ ] Pricing Plugin System
- [ ] Discount Plugin System
- [ ] Payment Plugin System
- [ ] Messaging Plugin System
- [ ] Document Plugin System

## Non-development tasks

Beyond the most important part of bringing the engine out to public, we will always invest time and money into these tasks:

- **Tech Best Practice (Continous Refactoring)**. We want to further establish technical best practice in our products like pointer-based paging in graphql or better exception/error handling

- **Community**. We will invest a big amount of time not only coding but also building up a dev-friendly community

- **Documentation**. We will release API docs, guides and example code along the way to make it exxtremely easy for a Javascript developer to start his own E-Commerce project.

- **Testing**. At the moment, 90% of the code is untested and we know this is bad. While we refactor and decouple / "unchain" the engine we also want to improve the stability
