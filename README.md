# Feature Testing

The following documents the feature testing framework for 

---

## Part 1: Getting Started / Quick Start

```npm run e2e:ui``` — To run locally through the Cypress UI

```npm run e2e``` — To run all the tests on a CLI for verification / as part of a CI build

---

## Part 2: Introduction / Preamble

### Prior Art

Testing terms can be ambigiuous. 

The following clarifies the terms used within this document: 

* **Unit Test:** A single module of code (a function / class method etc).
* **Application Test:** A logical / functional grouping of code modules / units. 
* **Journey Test:** A scenario that covers one or many applications as the user would define it. 

**Note:** "End To End" testing is an ambiguous term so is avoided completely in this document. 

### What is Feature Testing? 

Fetaure testing is a step of testing that is ran _after_ code is written and tested as a unit. 

But _before_ the application is integrated with other applications. 

This means feature testing has a few key characteristics: 

* Runs within a browser (typically)
* Mocks out any other application integrations (e.g. API / network calls)
* Runs fast enough to be a non-disruptive part of a regular devs code / commit cycle (< a couple of minutes)
* Should not duplicate tests written at a unit test level

---

## Part 3: Working With This Repo

### Directory Structure

All feature testing code is contained within the `/cypress` directory. 

All tests scenarios are contained within `integration/application/[directory_name]`.

All test states are contained within `integration/application/[directory_name]`.


### Selectors 

### Test State

In order to test the dashboard, the application is required to be setup with an initial state. Theses

// TODO: Explain the setup states

### Page Object Model
