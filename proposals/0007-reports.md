# Reports

* Proposal: [SE-0007](0007-reports.md)
* Authors: @pozylon
* Status: **Draft**
* Breaking: No

## Introduction

Reporting Dashboard in Unchained Admin Panel

## Motivation

Unchained users currently can't see a big picture of the orders that get processed
through the system.

## Proposed solution

Very simple Dashboard style index page for admin ui with some nice charts
that show the performance of the shop.

## Detailed design

Tasks:

- [ ] Define what charts we want to show in the first place and how far we should go
- [ ] Chart library evaluation
- [ ] Dashboard Page Design in Admin UI
- [ ] New admin queries to get data needed if that's the case at all

## Alternatives considered

* Don't implement it in the engine/admin ui and do the reporting directly against the database with some kind of data mining tool.
