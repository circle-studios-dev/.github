# Circle Studios Dev

Internal infrastructure, client projects, websites, and reusable systems for Circle Studios.

## Client systems

| Repository | Purpose |
|---|---|
| [client-amy-nelson](https://github.com/circle-studios-dev/client-amy-nelson) | Student database and course operations for Amy Nelson |
| [client-endless-access-student-db](https://github.com/circle-studios-dev/client-endless-access-student-db) | Student enrollment and activity logging for Endless Access |
| [client-every-student-db](https://github.com/circle-studios-dev/client-every-student-db) | Student enrollment database for Every |
| [client-maya-raichoora](https://github.com/circle-studios-dev/client-maya-raichoora) | Umbrella source for Maya Raichoora client builds, prototypes, and project phases |
| [client-realpars](https://github.com/circle-studios-dev/client-realpars) | Umbrella source for RealPars client builds, beginning with the PLC cohort splash review |
| [client-ruben-hassid](https://github.com/circle-studios-dev/client-ruben-hassid) | Student database, email capture, and exercise guide for Ruben Hassid |

## Client websites

| Repository | Purpose |
|---|---|
| [website-amy-nelson](https://github.com/circle-studios-dev/website-amy-nelson) | Amy Nelson website |
| [website-ruben-hassid](https://github.com/circle-studios-dev/website-ruben-hassid) | Ruben Hassid website |

## Internal apps

| Repository | Purpose |
|---|---|
| [internal-bpra-dashboard](https://github.com/circle-studios-dev/internal-bpra-dashboard) | BPRA course dashboard |
| [internal-client-dashboard](https://github.com/circle-studios-dev/internal-client-dashboard) | Client-facing dashboard proxied through the operations dashboard |
| [internal-ops-dashboard](https://github.com/circle-studios-dev/internal-ops-dashboard) | Process tracking, course calendar, and client management |
| [internal-product-overview-app](https://github.com/circle-studios-dev/internal-product-overview-app) | AI-assisted course product-overview generation |
| [internal-research-insights](https://github.com/circle-studios-dev/internal-research-insights) | Research-call synthesis from Notion |

## Infrastructure and templates

| Repository | Purpose |
|---|---|
| [demand-testing-funnel-template](https://github.com/circle-studios-dev/demand-testing-funnel-template) | Reusable demand-testing funnel |
| [infra-endless-cohort-snapshot](https://github.com/circle-studios-dev/infra-endless-cohort-snapshot) | Cohort snapshot utility for Endless Access |
| [infra-student-db-template](https://github.com/circle-studios-dev/infra-student-db-template) | Reusable client student-database boilerplate |

## Tools

| Repository | Purpose |
|---|---|
| [tool-circle-mcp](https://github.com/circle-studios-dev/tool-circle-mcp) | MCP server for the Circle API |
| [tool-remotion-explore](https://github.com/circle-studios-dev/tool-remotion-explore) | Video composition and highlight-reel experiments |
| [tool-wistia-mcp](https://github.com/circle-studios-dev/tool-wistia-mcp) | MCP server for Wistia |

## Studio systems

| Repository | Purpose |
|---|---|
| [circle-studios-skills](https://github.com/circle-studios-dev/circle-studios-skills) | Reviewed team/recovery mirror of the canonical vault skills |
| [ops-circle-studios](https://github.com/circle-studios-dev/ops-circle-studios) | Shared operations context, scripts, and course-delivery skills; separate from Linart's vault-skill mirror |

## Organization maintenance

| Repository | Purpose |
|---|---|
| [.github](https://github.com/circle-studios-dev/.github) | Organization profile and shared repository metadata |
| [bruce](https://github.com/circle-studios-dev/bruce) | Legacy name awaiting an explicit owner and classification decision |

## Repository conventions

- `client-<client>` — default private umbrella source for one client's builds, organized under `projects/<phase-or-project>/<build>/`
- `client-<client>-<system>` — dedicated client operational system when it needs an independent lifecycle
- `website-<client>` — dedicated production client website
- `internal-<system>` — internal Studio applications
- `infra-<capability>` or `<purpose>-template` — reusable infrastructure and templates
- `tool-<capability>` — reusable tools and experiments
- `ops-<area>` — Studio operations and methodology

New repositories are private by default. Put durable Circle Studios and client work in this organization; use personal GitHub only for genuinely personal projects. GitHub is canonical for executable build source, while the vault remains canonical for objectives, decisions, and project context. Every build push must refresh the repository README and CHANGELOG so a teammate or AI can continue from zero context.
