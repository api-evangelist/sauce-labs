# Sauce Labs (sauce-labs)

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Sauce Labs is a cloud-based cross-browser and mobile app testing platform trusted by over 100,000 customers worldwide. It provides a comprehensive REST API for managing test jobs, real and virtual devices, builds, and results across its global testing infrastructure. The platform supports automated testing with Appium, Espresso, XCUITest, and major CI/CD integrations, and includes an MCP server for AI agent integrations.

APIs.json: [https://raw.githubusercontent.com/api-evangelist/sauce-labs/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/sauce-labs/refs/heads/main/apis.yml)

Naftiko: [https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=sauce-labs-api-evangelist&utm_content=repo](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=sauce-labs-api-evangelist&utm_content=repo)

## Tags

- Testing
- Cross-Browser Testing
- Mobile Testing
- Real Devices
- Automation
- CI/CD
- Quality Assurance

## APIs

| Name | Description | Docs | OpenAPI |
|------|-------------|------|---------|
| Jobs API | Manage and retrieve test jobs on virtual and real device infrastructure | [Docs](https://docs.saucelabs.com/dev/api/jobs/) | [OpenAPI](https://raw.githubusercontent.com/saucelabs/sauce-docs/refs/heads/main/static/oas/sauce.json) |
| Real Device API | Access and control real Android and iOS devices | [Docs](https://docs.saucelabs.com/dev/api/rdc/) | [OpenAPI](https://raw.githubusercontent.com/saucelabs/sauce-docs/refs/heads/main/static/oas/rdc.json) |
| Real Device Access API | Programmatic session management for real devices | [Docs](https://docs.saucelabs.com/dev/api/rdc/) | [OpenAPI](https://raw.githubusercontent.com/saucelabs/sauce-docs/refs/heads/main/static/oas/real-device-access-api-spec.yaml) |
| Accounts API | Manage users, teams, and organizational settings | [Docs](https://docs.saucelabs.com/dev/api/) | [OpenAPI](https://raw.githubusercontent.com/saucelabs/sauce-docs/refs/heads/main/static/oas/accounts.yml) |
| Builds API | Track and manage CI/CD build groupings | [Docs](https://docs.saucelabs.com/dev/api/) | [OpenAPI](https://raw.githubusercontent.com/saucelabs/sauce-docs/refs/heads/main/static/oas/buildsv2.json) |
| Platform API | Query supported automation environments and status | [Docs](https://docs.saucelabs.com/dev/api/platform/) | — |
| Sauce Connect API | Manage secure tunnels for private network testing | [Docs](https://docs.saucelabs.com/dev/api/connect/) | — |
| Storage API | Upload and manage app files and test artifacts | [Docs](https://docs.saucelabs.com/dev/api/) | — |
| Test Authoring API | Author and manage test suites programmatically | [Docs](https://docs.saucelabs.com/dev/api/) | [OpenAPI](https://raw.githubusercontent.com/saucelabs/sauce-docs/refs/heads/main/static/oas/test-authoring-api.json) |
| Performance API | Access web performance metrics from test runs | [Docs](https://docs.saucelabs.com/dev/api/) | [OpenAPI](https://raw.githubusercontent.com/saucelabs/sauce-docs/refs/heads/main/static/oas/performance.json) |

## Plans, Rate Limits, and FinOps

- [Plans & Pricing](plans/sauce-labs-plans-pricing.yml) — Live Testing ($39/mo), Virtual Device Cloud ($149/mo), Real Device Cloud ($199/mo), Enterprise (custom)
- [Rate Limits](rate-limits/sauce-labs-rate-limits.yml) — 10 req/sec (3,500/hr) authenticated; 2 req/min unauthenticated; HTTP 429 on breach
- [FinOps](finops/sauce-labs-finops.yml) — Subscription-based, metered by concurrent sessions; FOCUS-aligned cost tracking

## Timestamps

- Created: 2026-06-12
- Modified: 2026-06-12

## Common Properties

| Type | URL |
|------|-----|
| Website | https://saucelabs.com |
| Documentation | https://docs.saucelabs.com/dev/api/ |
| GitHub Organization | https://github.com/saucelabs |
| LinkedIn | https://www.linkedin.com/company/sauce-labs |
| X / Twitter | https://twitter.com/saucelabs |
| Blog | https://saucelabs.com/resources/blog |
| Pricing | https://saucelabs.com/pricing |
| Status Page | https://status.saucelabs.com/ |
| Changelog | https://changelog.saucelabs.com/en |
| MCP Server | https://github.com/saucelabs/sauce-api-mcp |
| Node.js SDK | https://github.com/saucelabs/node-saucelabs |

## Maintainers

- Kin Lane / kin@apievangelist.com
