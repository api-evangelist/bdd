# BDD (Behavior-Driven Development) (bdd)

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

Behavior-Driven Development (BDD) is a software development methodology that combines test-driven development with domain-driven design, encouraging collaboration between developers, QA, and business stakeholders through human-readable test scenarios. The BDD ecosystem includes frameworks, tools, and data providers that enable teams to write specifications in Gherkin syntax (Given-When-Then) and automate those scenarios as executable tests across APIs, UIs, and microservices.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/bdd/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Automation, BDD, Software Development, Testing, Gherkin, Quality Assurance

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-04-19

## APIs

### Cucumber
Cucumber is the world's most popular BDD framework, supporting Java, JavaScript, Ruby, Python, and C#. It uses Gherkin syntax for writing human-readable test scenarios and provides integrations with all major test runners, CI/CD platforms, and API testing tools.

**Human URL:** [https://cucumber.io/](https://cucumber.io/)

#### Tags:

 - BDD, Testing, Gherkin, Java, JavaScript

#### Properties

- [Documentation](https://cucumber.io/docs/cucumber/)
- [GettingStarted](https://cucumber.io/docs/guides/10-minute-tutorial/)
- [GitHubRepository](https://github.com/cucumber/cucumber-jvm)

### SpecFlow
SpecFlow is a BDD framework for .NET developers, enabling teams to write behavior specifications in Gherkin and execute them in C# applications. SpecFlow+ Runner and SpecFlow+ LivingDoc provide enhanced test execution and living documentation capabilities.

**Human URL:** [https://specflow.org/](https://specflow.org/)

#### Tags:

 - BDD, Testing, Gherkin, .NET, C#

#### Properties

- [Documentation](https://docs.specflow.org/)
- [GettingStarted](https://docs.specflow.org/projects/specflow/en/latest/Getting-Started/)

### Behave
Behave is a Python BDD framework inspired by Cucumber that enables teams to write behavior specifications in Gherkin syntax and execute them using Python. It integrates with Django, Flask, FastAPI, and REST API testing tools.

**Human URL:** [https://behave.readthedocs.io/](https://behave.readthedocs.io/)

#### Tags:

 - BDD, Testing, Gherkin, Python

#### Properties

- [Documentation](https://behave.readthedocs.io/en/stable/)
- [GitHubRepository](https://github.com/behave/behave)

### Karate
Karate is a modern open-source BDD framework that unifies API testing, UI automation, performance testing, and mocking in a single framework. It uses a Gherkin-like DSL and is particularly powerful for REST and GraphQL API testing.

**Human URL:** [https://karatelabs.github.io/karate/](https://karatelabs.github.io/karate/)

#### Tags:

 - BDD, API Testing, REST Testing, Performance Testing

#### Properties

- [Documentation](https://karatelabs.github.io/karate/)
- [GitHubRepository](https://github.com/karatelabs/karate)

### JBehave
JBehave is a pioneering BDD framework for Java and JVM languages. It supports web, REST API, and microservices testing with integration for JUnit, Spring, Maven, and Gradle.

**Human URL:** [https://jbehave.org/](https://jbehave.org/)

#### Tags:

 - BDD, Testing, Java, JVM

#### Properties

- [Documentation](https://jbehave.org/reference/latest/)
- [GitHubRepository](https://github.com/jbehave/jbehave-core)

## Common Properties

- [Website](https://cucumber.io/)
- [Documentation](https://cucumber.io/docs/)
- [GitHubOrganization](https://github.com/cucumber)

## Features

| Name | Description |
|------|-------------|
| Gherkin Syntax | Human-readable Given-When-Then scenario language for describing software behavior as executable specifications. |
| Multi-Language Support | BDD frameworks available for Java, JavaScript, Python, Ruby, C#, Go, and most other programming languages. |
| API Testing Integration | Frameworks like Karate and Cucumber enable BDD-style API testing for REST, GraphQL, and SOAP services. |
| Living Documentation | BDD scenarios serve as living documentation that stays synchronized with the actual system behavior. |
| CI/CD Integration | All major BDD frameworks integrate with Jenkins, GitHub Actions, GitLab CI, CircleCI, and other CI/CD platforms. |

## Use Cases

| Name | Description |
|------|-------------|
| API Contract Testing | Use BDD frameworks to write executable API contract tests that verify request/response behavior from a business perspective. |
| Acceptance Testing | Write acceptance tests in Gherkin that business stakeholders can read and validate before implementation begins. |
| Regression Testing | Build a regression test suite using BDD scenarios that can be run automatically on every code change. |
| Microservices Testing | Test microservice integrations using BDD frameworks with HTTP clients and mock servers. |

## Integrations

| Name | Description |
|------|-------------|
| JUnit | Java test runner integration for executing Cucumber and JBehave scenarios in Java projects. |
| Playwright | Browser automation integration for UI-level BDD testing with Cucumber or SpecFlow. |
| REST Assured | Java DSL for REST API testing commonly used with Cucumber for BDD-style API test suites. |
| Postman | API testing platform that supports BDD-style test writing in the test scripts section. |
| Allure | Test reporting framework that integrates with Cucumber, SpecFlow, and other BDD frameworks for rich HTML reports. |

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
