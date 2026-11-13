# Awesome-Developer-Platform-SDKs

## Top Developer Platform & SDKs Ecosystem

**Curated List of SaaS Platforms & Open-Source GitHub Projects**  
*Focused on API Design, SDK Generation & Developer Experience Infrastructure*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Developer Platform & SDKs**. These tools provide the foundational infrastructure for building, testing, and distributing APIs and client libraries—covering API gateways, SDK generators, documentation portals, and developer portals that reduce integration friction for third-party developers.

**Examples** include Freshworks Developer Platform, Salesforce Developer Platform, Zendesk Developer Platform, Twilio, GitHub, Stripe, Shopify, Atlassian, Slack, and Postman (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted API tooling, open-source SDK generation, and community-driven developer portals—ideal for organizations seeking transparency and predictable costs over per-seat or per-API-call SaaS billing. The open-source landscape is genuinely functional: **OpenAPI Generator** and **Speakeasy** automate SDK creation , **Hoppscotch** and **Bruno** provide Postman alternatives , and **Backstage** delivers a complete developer portal .

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Pricing (Starting) | Free Tier / Trial Limits |
|---------|-------------|-------------------|--------------------------|
| **[Freshworks Developer Platform](https://developers.freshworks.com/)** | Platform for building apps that run inside Freshworks products (Freshdesk, Freshservice, Freshchat, Freshcaller, Freshsales). Provides **FDK (Freshworks Developer Kit)** CLI, App SDK, REST APIs, webhooks, and serverless app support. Apps render in iframes at designated placeholders. | $19/agent/month (Growth plan, billed annually) | 14-day free trial; free developer account for app development & testing in local sandbox |
| **[Salesforce Developer Platform](https://developer.salesforce.com/)** | Enterprise development platform with Agentforce, Data 360, and Salesforce DX. **Agent Script** language for agent logic, **Agentforce Mobile SDK** for embedding agents in iOS/Android/React Native, and **Metadata API** for deployment. Open-source Agent Script repository available. | $25/user/month (Starter Suite, billed annually) | Free Developer Edition org (free forever: up to 2-5 developer licenses, 5-10 MB data storage, 20 MB file storage, and 15,000 daily API calls) |
| **[Zendesk Developer Platform](https://developer.zendesk.com/)** | Sunshine Platform for building apps, integrations, and automations. **REST APIs**, **ZAF (Zendesk Apps Framework)**, **Web Widget SDKs**, **Integration Services (ZIS)**, and **webhooks**. Apps can be published to the Zendesk Marketplace. | $19/agent/month (Support Team, billed annually) | 14-day free trial (full Zendesk Suite Professional access with no credit card required); free developer sponsor accounts via developer program |
| **[Twilio](https://www.twilio.com/)** | Communications platform with **1,500+ API endpoints** across 30+ products. **MCP Server** for AI coding agents with semantic search. **Conversation Relay** for connecting AI agents to voice calls. SDKs for Node.js, Python, Ruby, Java, PHP, C#, and Go. | $0.0083/message segment (SMS outbound US) + $1.15/month per local number | 30-day free trial with 100 free SMS messages, 100 WhatsApp messages, and 75 voice minutes to verified numbers |
| **[GitHub Developer Platform](https://docs.github.com/en/developers)** | REST and GraphQL APIs for repositories, issues, pull requests, Actions, and more. **Octokit SDK** for TypeScript/Node.js. **Webhooks** with signature validation. OpenAPI specification available for code generation. | $4/user/month (Team plan, billed annually or monthly) | Free forever (unlimited public/private repos, 2,000 CI/CD Actions minutes/month, 500 MB Packages storage, and 5,000 authenticated API requests/hour) |
| **[Stripe](https://stripe.com/docs/api)** | Payments REST API with **644 operations** across payments, billing, Connect, Issuing, Treasury, Terminal, Radar, and Tax. **OpenAPI 3.0 document** published under MIT license. Official SDKs for all major languages. | 2.9% + $0.30 per successful online transaction (standard US cards) | Free forever full Test Mode (unlimited test API calls, simulated charges, card disputes, webhooks, and sandbox events with test keys) |
| **[Shopify](https://shopify.dev/)** | Commerce platform with **GraphQL Admin API** (primary), REST (legacy), Storefront API, and **Shopify Functions**. Official CLI (`@shopify/cli`), app templates, and **Hydrogen** framework for headless storefronts. | $29/month (Basic plan, billed annually) | Free forever Partner account (unlimited developer stores for building, testing apps, themes, and staging deployments at no cost) |
| **[Atlassian Developer Platform](https://developer.atlassian.com/)** | Platform for building apps for Jira, Confluence, and other Atlassian products. **Forge** (serverless) is the future; **Connect** reaches end of support **January 31, 2027**. OAuth 2.0 (3LO) for authentication. App migration path from Connect to Forge documented. | $7.91/user/month (Jira Cloud Standard, billed annually) | Free forever plan (up to 10 users, 2 GB file storage, 150 automation runs/month for Jira/Confluence Cloud, and free Forge app development sandbox) |
| **[Slack API](https://api.slack.com/)** | Messaging platform with **Web API**, **Events API**, **Socket Mode**, and **Bolt** SDKs for Python, JavaScript, and Java. OAuth 2.0 with bot/user token scopes. Token rotation supported. | $7.25/user/month (Pro plan, billed annually) | Free forever plan (90 days message & file history, up to 10 app integrations, 1:1 huddles, and free sandbox development workspaces) |
| **[Postman](https://www.postman.com/)** | API development environment with Collections, Mock Servers, Monitors, and **Postman CLI**. March 2026 restructure made collection runs unlimited but removed team workspaces from the free plan. | $9/user/month (Solo plan, billed annually) | Free forever plan (single user only, unlimited collection runs, 3 active mock servers, up to 10,000 mock server/monitor calls/month) |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[OpenAPI Generator](https://github.com/OpenAPITools/openapi-generator)** | [![Stars](https://img.shields.io/github/stars/OpenAPITools/openapi-generator?style=social&color=white)](https://github.com/OpenAPITools/openapi-generator/stargazers) | **The most widely used open-source SDK generator.** Generates client libraries, server stubs, documentation, and configuration from OpenAPI 2.0/3.x specifications. Supports **50+ languages and frameworks** including Java, Python, TypeScript, Go, Rust, C#, PHP, Ruby, and Swift. Apache 2.0 licensed. The standard tool for organizations building their own SDKs from API specs. |
| **[Speakeasy](https://github.com/speakeasy-api/speakeasy)** | [![Stars](https://img.shields.io/github/stars/speakeasy-api/speakeasy?style=social&color=white)](https://github.com/speakeasy-api/speakeasy/stargazers) | **Open-source SDK generator focused on developer experience.** Generates idiomatic, type-safe SDKs from OpenAPI specs with built-in auth, pagination, retries, and error handling. Supports TypeScript, Python, Go, Java, and more. CLI and GitHub Actions integration for CI/CD SDK generation. |
| **[Hoppscotch](https://github.com/hoppscotch/hoppscotch)** | [![Stars](https://img.shields.io/github/stars/hoppscotch/hoppscotch?style=social&color=white)](https://github.com/hoppscotch/hoppscotch/stargazers) | **Open-source API development ecosystem (Postman alternative).** Lightweight web-based API client with collections, environments, and team collaboration. Self-hostable. The commercial cloud adds Enterprise controls on top . |
| **[Bruno](https://github.com/usebruno/bruno)** | [![Stars](https://img.shields.io/github/stars/usebruno/bruno?style=social&color=white)](https://github.com/usebruno/bruno/stargazers) | Offline-first, Git-friendly API client. Stores collections as plain files for version control; no cloud sync required. Designed for teams that want collaboration via Git rather than a proprietary cloud workspace . |
| **[Backstage](https://github.com/backstage/backstage)** | [![Stars](https://img.shields.io/github/stars/backstage/backstage?style=social&color=white)](https://github.com/backstage/backstage/stargazers) | **CNCF Incubation developer portal framework.** Centralized software catalog for APIs, services, and documentation. TechDocs enables "docs like code"; plugins extend workspace collaboration. Self-hosted . |

### Additional Strong Open-Source Options

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Redocly CLI](https://github.com/Redocly/redocly-cli)** | [![Stars](https://img.shields.io/github/stars/Redocly/redocly-cli?style=social&color=white)](https://github.com/Redocly/redocly-cli/stargazers) | Open-source OpenAPI linting, bundling, and documentation generation. Enforces API style guides and generates beautiful reference docs from OpenAPI specs. |
| **[Scalar](https://github.com/scalar/scalar)** | [![Stars](https://img.shields.io/github/stars/scalar/scalar?style=social&color=white)](https://github.com/scalar/scalar/stargazers) | Open-source API reference and client generation. Generates interactive API documentation from OpenAPI specs with built-in API client playground. |

**Frameworks for building custom systems**: Combine **OpenAPI Generator** or **Speakeasy** for SDK generation from your API specs, **Redocly CLI** for API linting and documentation, **Backstage** for a developer portal, and **Hoppscotch** or **Bruno** for API testing—creating a fully open-source developer platform stack without per-seat SaaS fees.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Developer platforms handle API credentials and potentially sensitive application data; enforce least-privilege scopes, token rotation, and audit logging.
- **Platform lock-in and lifecycle risks vary significantly.** Atlassian's **Connect** reaches end of support **January 31, 2027**—apps must migrate to **Forge** . Freshworks apps run in iframes with FDK and Node.js version requirements . Zendesk uses **ZAF** and **ZIS** with Sunshine Platform . **Open-source SDK generation is genuinely viable**: OpenAPI Generator supports 50+ languages and Speakeasy focuses on idiomatic developer experience . **Postman's free tier is now single-user only** as of March 2026—teams needing collaboration must migrate to Hoppscotch, Bruno, or paid Postman plans .

---

**Made for API developers, platform engineers, and teams building developer-facing infrastructure.**  
Let's make developer platforms and SDKs more open, accessible, and developer-friendly.
