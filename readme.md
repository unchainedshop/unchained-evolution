# unchained.shop Evolution

This repository tracks the ongoing evolution of the unchained shop. It contains:

* A general overview of all the software components that are part of the platform
* Goals for upcoming unchained engine releases (this document).
* Software Architecture Policies

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
- [ ] Umbrella Repository

**Core Package Refactorings needed**:
- [x] Delivery Plugin System
- [x] Warehousing Plugin System
- [ ] Pricing Plugin System
- [ ] Discount Plugin System
- [ ] Payment Plugin System
- [ ] Messaging Plugin System
- [ ] Document Plugin System

### Other Improvements

Beyond the most important part of bringing the engine out to public, we will invest time and money into these tasks:

- **Tech Best Practice (Continous Refactoring)**. We want to further establish technical best practice in our products like pointer-based paging in graphql or better exception/error handling

- **Community**. We will invest a big amount of time not only coding but also building up a dev-friendly community

- **Documentation**. We will release API docs, guides and example code along the way to make it exxtremely easy for a Javascript developer to start his own E-Commerce project.

- **Testing**. At the moment, 90% of the code is untested and we know this is bad. While we refactor and decouple / "unchain" the engine we also want to improve the stability
