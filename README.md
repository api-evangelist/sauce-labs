# Sauce Labs (sauce-labs)

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
