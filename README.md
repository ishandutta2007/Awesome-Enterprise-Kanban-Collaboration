# Awesome-Enterprise-Kanban-Collaboration

# Awesome Enterprise Kanban Collaboration

> A curated list of top Enterprise Kanban Collaboration platforms — both SaaS/Hosted commercial solutions and open-source alternatives for self-hosted visual project management and workflow collaboration.  
> 🌟 Star this repo if you find it useful! 🌟

---

## 📋 Table of Contents

- [SaaS / Hosted Platforms](#-saas--hosted-platforms)
  - [Trello Enterprise](#trello-enterprise)
  - [Asana Enterprise](#asana-enterprise)
  - [Monday.com Enterprise](#mondaycom-enterprise)
  - [Planview AgilePlace](#planview-agileplace)
  - [SwiftKanban](#swiftkanban)
  - [Targetprocess](#targetprocess)
  - [Kanbanize (Businessmap)](#kanbanize-businessmap)
  - [ClickUp Enterprise](#clickup-enterprise)
  - [Wrike Enterprise](#wrike-enterprise)
  - [Smartsheet](#smartsheet)
- [Open-Source Software](#-open-source-software)
  - [Planka](#planka)
  - [WeKan](#wekan)
  - [Kan.bn](#kanbn)
  - [Vikunja](#vikunja)
  - [Taiga](#taiga)
  - [Worklenz](#worklenz)
  - [Kanboard](#kanboard)
  - [Werkyn](#werkyn)
  - [Nextcloud Deck](#nextcloud-deck)
- [Comparison at a Glance](#-comparison-at-a-glance)
- [Contributing](#-contributing)

---

## 🟦 SaaS / Hosted Platforms

Commercial, cloud-hosted Enterprise Kanban Collaboration platforms. These are not open-source but are included as reference points for feature comparison.

### Trello Enterprise
**Type:** Visual Kanban pioneer  
The original Kanban-style board tool, now part of Atlassian. Enterprise tier adds advanced admin controls, organization-wide permissions, and security features. Pricing is per-user, with unlimited boards and automation attached to paid tiers. No self-hosted edition available [citation:6].  
**Best for:** Teams wanting the most familiar Kanban experience with enterprise governance from Atlassian.

### Asana Enterprise
**Type:** Work management with Kanban views  
Offers Kanban boards alongside list, timeline, and calendar views. Enterprise features include advanced reporting, workload management, and SAML SSO. Pricing scales per-user; no self-hosted option.  
**Best for:** Organizations wanting Kanban within a broader work management platform.

### Monday.com Enterprise
**Type:** Work OS with Kanban boards  
A flexible work operating system with customizable Kanban boards, automation recipes, and dashboards. Enterprise tier adds advanced permissions, audit logs, and dedicated support. Pricing is per-seat with tiered feature gating.  
**Best for:** Teams wanting highly customizable boards with strong automation capabilities.

### Planview AgilePlace
**Type:** Enterprise Kanban and lean portfolio management  
Formerly LeanKit, focused on enterprise-scale Kanban with lean portfolio management, dependency tracking, and analytics. Suited for organizations practicing lean/agile at scale across multiple teams. Pricing is quote-based.  
**Best for:** Enterprises needing Kanban connected to portfolio-level planning and lean governance.

### SwiftKanban
**Type:** Enterprise Kanban and Scrum  
Provides Kanban and Scrum boards with analytics, WIP limits, and enterprise reporting. Includes features for distributed teams and compliance. Pricing is per-user with tiered plans.  
**Best for:** Teams wanting dedicated Kanban/Scrum tooling with enterprise reporting.

### Targetprocess
**Type:** Agile project management with Kanban  
Supports Kanban, Scrum, and SAFe frameworks with customizable views. Known for flexibility in modeling complex workflows and portfolio management. Pricing is per-user.  
**Best for:** Organizations practicing scaled agile needing flexible Kanban within a broader agile suite.

### Kanbanize (Businessmap)
**Type:** Enterprise Kanban platform  
Focused on enterprise Kanban with rules-based automation, analytics, and portfolio Kanban. Features include WIP limits, cycle time analytics, and dependency visualization. Pricing is quote-based.  
**Best for:** Enterprises wanting deep Kanban analytics and automation at scale.

### ClickUp Enterprise
**Type:** All-in-one productivity with Kanban  
Offers Kanban boards alongside docs, goals, and time tracking. Enterprise tier adds advanced permissions, SSO, and dedicated success management. Pricing is per-user with a generous free tier.  
**Best for:** Teams wanting Kanban within an all-in-one productivity suite.

### Wrike Enterprise
**Type:** Work management with Kanban  
Provides Kanban boards within a broader project management platform. Enterprise features include custom workflows, reporting, and security controls. Pricing is per-user with tiered plans.  
**Best for:** Teams wanting Kanban integrated with project portfolio management.

### Smartsheet
**Type:** Spreadsheet-based work management with Kanban  
Offers Kanban views on top of its spreadsheet-like grid. Enterprise features include governance, reporting, and integrations. Pricing is per-user with tiered plans.  
**Best for:** Teams already using Smartsheet grids wanting Kanban visualization.

---

## 🟩 Open-Source Software

Self-hosted, community-driven Kanban Collaboration platforms. All listed projects offer source code you can deploy on your own infrastructure.

### Planka
**Stack:** Node.js / React / PostgreSQL | **License:** Fair-code (Community) / Pro [citation:1][citation:7]  
A modern, real-time Kanban board positioned as an open-source Trello alternative. Features include drag-and-drop boards, lists, and cards; Markdown descriptions; file attachments; OIDC single sign-on; 100+ notification providers via Apprise; webhooks; and a documented REST API [citation:1][citation:6]. Real-time syncing via WebSocket means no refresh needed. The Community edition is self-hostable with PostgreSQL; a Pro edition adds calendar, timeline, map views, guest roles, SSO, and PDF export, and upgrades in place [citation:8]. Deploys as a single Docker image [citation:1].  
**Best for:** Teams wanting a polished, real-time Trello-like experience with modern auth and self-hosted control.

### WeKan
**Stack:** Meteor / Node.js / MongoDB (or FerretDB) | **License:** MIT [citation:6][citation:14]  
The closest open-source clone of Trello's screen, including swimlanes. Actively maintained with frequent releases (v8.35 as of February 2026) [citation:14]. Features include WIP limits, custom fields, card voting, time tracking, subtasks, and granular permissions. Supports LDAP, OIDC, SAML, and OAuth2 authentication. Default Docker Compose now runs on FerretDB with embedded SQLite, though MongoDB remains an option [citation:6]. **Caveats:** Only the newest version is supported due to security issues in older Node.js runtimes; no undo yet; some bugs can require manual database fixes [citation:6].  
**Best for:** Teams wanting the most Trello-like experience with swimlanes and enterprise auth options.

### Kan.bn
**Stack:** Next.js / TypeScript / PostgreSQL | **License:** AGPL-3.0 [citation:8][citation:15]  
A newer open-source Trello alternative with unlimited boards, lists, and cards. Features include Trello import, labels, filters, comments, activity logs, templates, and API/webhooks. Notably includes an MCP server for AI agent control of boards [citation:15]. Offers both a hosted free plan and self-hosting via Docker. Actively developed [citation:8].  
**Best for:** Teams wanting a modern Trello alternative with AI agent integration and Trello import.

### Vikunja
**Stack:** Go / SQLite or PostgreSQL | **License:** AGPLv3 [citation:8]  
Started as a to-do app and evolved into a project management tool with list, Kanban, Gantt, and table views. A single Go binary or Docker deployment makes it lightweight. A paid hosted option (Vikunja Cloud) also exists [citation:8].  
**Best for:** Teams wanting personal task lists and shared Kanban boards in one place with a lightweight footprint.

### Taiga
**Stack:** Python / Django | **License:** AGPL-3.0 (open source) [citation:3]  
Built around agile project work, combining Kanban and Scrum boards with sprint planning, backlog management, and issue tracking. Supports both cloud and self-hosted deployments. Integrates with GitHub, GitLab, Slack, and Zapier [citation:3].  
**Best for:** Agile teams needing Kanban alongside Scrum and issue tracking.

### Worklenz
**Stack:** React / Node.js / PostgreSQL / S3 | **License:** AGPL-3.0 [citation:4]  
A project management tool with Kanban boards, recurring tasks, custom columns, time tracking, and resource planning. Version 2.0 added an extended Kanban board, user-defined fields, and dark mode. Requires Node.js 18+, PostgreSQL 15+, and S3-compatible storage. Deploys via Docker [citation:4].  
**Best for:** Teams wanting Kanban with time tracking and resource planning in a self-hosted package.

### Kanboard
**Stack:** PHP / SQLite or PostgreSQL | **License:** MIT [citation:6][citation:8]  
A deliberately minimal Kanban tool focused strictly on the Kanban methodology. Supports WIP limits (highlights over-cap columns), swimlanes, and a simple interface. **Important:** The README states the application is in maintenance mode — no new major features, only small fixes and community contributions [citation:6][citation:8].  
**Best for:** Small teams wanting a stable, finished Kanban tool that won't change under them.

### Werkyn
**Stack:** React / Fastify / PostgreSQL | **License:** AGPL-3.0 [citation:2]  
A development-preview project management and collaboration platform with Kanban boards, list/calendar views, task properties (priorities, subtasks, dependencies, custom fields), wiki/documentation, and file management. Includes real-time updates via WebSocket and a command palette. **Warning:** The project explicitly states it is a development preview with potential security flaws and should not be used in production [citation:2].  
**Best for:** Early adopters wanting to evaluate a promising Kanban + wiki platform (not yet production-ready).

### Nextcloud Deck
**Stack:** PHP / Nextcloud | **License:** AGPL [citation:13]  
An official Nextcloud app that adds Kanban boards to a self-hosted private cloud. Cards can link directly to Nextcloud files without duplication, boards can be shared with Nextcloud groups and circles, and due dates sync with Nextcloud Calendar. No standalone deployment — requires a Nextcloud server [citation:13].  
**Best for:** Teams already running Nextcloud wanting Kanban integrated into their existing private cloud.

---

## 📊 Comparison at a Glance

| Software | License | Stack | Real-time | Self-Hosted | Best For |
|----------|---------|-------|-----------|-------------|----------|
| **Trello Enterprise** | Proprietary | Cloud | ✅ | ❌ | Familiar Kanban + Atlassian |
| **Asana Enterprise** | Proprietary | Cloud | ✅ | ❌ | Kanban within work management |
| **Monday.com Enterprise** | Proprietary | Cloud | ✅ | ❌ | Customizable boards + automation |
| **Planview AgilePlace** | Proprietary | Cloud | ✅ | ❌ | Enterprise lean portfolio |
| **Kanbanize** | Proprietary | Cloud | ✅ | ❌ | Deep Kanban analytics |
| **Planka** | Fair-code / Pro | Node.js/React | ✅ | ✅ | Polished Trello alternative |
| **WeKan** | MIT | Meteor/MongoDB | ✅ | ✅ | Closest Trello clone + swimlanes |
| **Kan.bn** | AGPL-3.0 | Next.js | ✅ | ✅ | Modern + AI agent control |
| **Vikunja** | AGPLv3 | Go | ✅ | ✅ | Personal + team hybrid |
| **Taiga** | AGPL-3.0 | Python/Django | ✅ | ✅ | Kanban + Scrum + issues |
| **Worklenz** | AGPL-3.0 | React/Node | ✅ | ✅ | Kanban + time tracking |
| **Kanboard** | MIT | PHP | ❌ | ✅ | Minimal, finished tool |
| **Werkyn** | AGPL-3.0 | React/Fastify | ✅ | ✅ | Preview: Kanban + wiki |
| **Nextcloud Deck** | AGPL | PHP/Nextcloud | ✅ | ✅ (Nextcloud) | Nextcloud ecosystem |

---

## 🤝 Contributing

Contributions are welcome! If you know of an open-source Enterprise Kanban Collaboration platform that should be listed here, please open a pull request with:

- Project name and URL
- Brief description (1–2 sentences)
- Stack and license
- Why it stands out

Please ensure the project is actively maintained (releases within the last 12 months) and genuinely open-source.

---

## 📄 License

This list is released under CC0 1.0 Universal (Public Domain). The software projects listed retain their respective licenses.

---

⭐ **If this list helped you discover a useful tool, please star the repo!** ⭐
