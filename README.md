# Awesome-Developer-Platform-SDKs

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![GitHub Stars](https://img.shields.io/github/stars/ishandutta2007/Awesome-Developer-Platform-SDKs?style=social)](https://github.com/ishandutta2007/Awesome-Developer-Platform-SDKs/stargazers)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/ishandutta2007/Awesome-Developer-Platform-SDKs/pulls)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

> A curated list of top SaaS developer platforms, SDK generators, API gateways, documentation portals, and open-source developer experience (DevEx) tooling ecosystems.

## Overview & Developer Experience Infrastructure

**Curated List of SaaS Platforms & Open-Source GitHub Projects**  
*Focused on API Design, SDK Generation, API Gateways & Developer Experience Infrastructure*  
**Last updated: March 2026**

This repository tracks notable **SaaS developer platforms** and **open-source developer platform projects**. These tools provide the foundational infrastructure for building, testing, distributing, and managing APIs and client SDK libraries—covering API gateways, automated client SDK generators, interactive documentation portals, and internal developer portals (IDPs) that minimize integration friction for third-party and internal engineers.

- **Enterprise SaaS category leaders**: Shopify, Salesforce, Stripe, GitHub, Atlassian, Twilio, Slack, Zendesk, Freshworks, and Postman.
- **Open-source infrastructure**: High-performance API gateways (**Traefik**, **Kong Gateway**), Postman alternatives (**Hoppscotch**, **Bruno**), SDK generation engines (**OpenAPI Generator**, **Swagger Codegen**, **Fern**, **Speakeasy**), developer portals (**Backstage**), and interactive API documentation (**Scalar**, **Swagger UI**).

Contributions welcome! Open a PR to add or update entries. Keep descriptions factual, include official URLs, and follow the contribution guidelines.

## Table of Contents
- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The global API management and developer platform tooling sector is estimated at **$8.7B to $10.6B** (projected to reach **$30B+ by the early 2030s** at an 18–22% CAGR). The market is **moderately to highly fragmented** rather than winner-take-all; while cloud giants and legacy CRM/workflow ecosystems anchor enterprise developer suites, the explosion of microservices, AI agents, MCP (Model Context Protocol), and edge infrastructure has created an expanding multi-vendor ecosystem spanning specialized API gateways, open-source SDK engines, and headless developer portals.

## SaaS/Hosted Platforms

| Product | Company Scale (Valuation / Market Cap / Revenue) | Description | Pricing (Starting) | Free Tier / Trial Limits |
|---------|--------------------------------------------------|-------------|-------------------|--------------------------|
| **[Shopify](https://shopify.dev/)** | ~$190B Market Cap (Public: SHOP; ~$8.9B+ Annual Revenue) | Commerce platform with **GraphQL Admin API** (primary), REST (legacy), Storefront API, and **Shopify Functions**. Official CLI (`@shopify/cli`), app templates, and **Hydrogen** framework for headless storefronts. | $29/month (Basic plan, billed annually) | Free forever Partner account (unlimited developer stores for building, testing apps, themes, and staging deployments at no cost) |
| **[Salesforce Developer Platform](https://developer.salesforce.com/)** | ~$180B Market Cap (Public: CRM; ~$41.5B Annual Revenue) | Enterprise development platform with Agentforce, Data 360, and Salesforce DX. **Agent Script** language for agent logic, **Agentforce Mobile SDK** for embedding agents in iOS/Android/React Native, and **Metadata API** for deployment. Open-source Agent Script repository available. | $25/user/month (Starter Suite, billed annually) | Free Developer Edition org (free forever: up to 2-5 developer licenses, 5-10 MB data storage, 20 MB file storage, and 15,000 daily API calls) |
| **[Stripe](https://stripe.com/docs/api)** | ~$159B Valuation (Private; ~$14B+ Annual Net Revenue) | Payments REST API with **644 operations** across payments, billing, Connect, Issuing, Treasury, Terminal, Radar, and Tax. **OpenAPI 3.0 document** published under MIT license. Official SDKs for all major languages. | 2.9% + $0.30 per successful online transaction (standard US cards) | Free forever full Test Mode (unlimited test API calls, simulated charges, card disputes, webhooks, and sandbox events with test keys) |
| **[GitHub Developer Platform](https://docs.github.com/en/developers)** | ~$100B+ Valuation / $2B+ ARR (Acquired by Microsoft for $7.5B; parent MSFT ~$3.1T Market Cap) | REST and GraphQL APIs for repositories, issues, pull requests, Actions, and more. **Octokit SDK** for TypeScript/Node.js. **Webhooks** with signature validation. OpenAPI specification available for code generation. | $4/user/month (Team plan, billed annually or monthly) | Free forever (unlimited public/private repos, 2,000 CI/CD Actions minutes/month, 500 MB Packages storage, and 5,000 authenticated API requests/hour) |
| **[Atlassian Developer Platform](https://developer.atlassian.com/)** | ~$38B Market Cap (Public: TEAM; ~$4.4B+ Annual Revenue) | Platform for building apps for Jira, Confluence, and other Atlassian products. **Forge** (serverless) is the future; **Connect** reaches end of support **January 31, 2027**. OAuth 2.0 (3LO) for authentication. App migration path from Connect to Forge documented. | $7.91/user/month (Jira Cloud Standard, billed annually) | Free forever plan (up to 10 users, 2 GB file storage, 150 automation runs/month for Jira/Confluence Cloud, and free Forge app development sandbox) |
| **[Twilio](https://www.twilio.com/)** | ~$34B Market Cap (Public: TWLO; ~$4.4B+ Annual Revenue) | Communications platform with **1,500+ API endpoints** across 30+ products. **MCP Server** for AI coding agents with semantic search. **Conversation Relay** for connecting AI agents to voice calls. SDKs for Node.js, Python, Ruby, Java, PHP, C#, and Go. | $0.0083/message segment (SMS outbound US) + $1.15/month per local number | 30-day free trial with 100 free SMS messages, 100 WhatsApp messages, and 75 voice minutes to verified numbers |
| **[Slack API](https://api.slack.com/)** | ~$28B Acquisition Valuation / ~$1.7B Revenue (Salesforce subsidiary; acquired for $27.7B) | Messaging platform with **Web API**, **Events API**, **Socket Mode**, and **Bolt** SDKs for Python, JavaScript, and Java. OAuth 2.0 with bot/user token scopes. Token rotation supported. | $7.25/user/month (Pro plan, billed annually) | Free forever plan (90 days message & file history, up to 10 app integrations, 1:1 huddles, and free sandbox development workspaces) |
| **[Zendesk Developer Platform](https://developer.zendesk.com/)** | ~$10.2B Valuation (Acquired by Permira & Hellman & Friedman for $10.2B; ~$1.7B Revenue) | Sunshine Platform for building apps, integrations, and automations. **REST APIs**, **ZAF (Zendesk Apps Framework)**, **Web Widget SDKs**, **Integration Services (ZIS)**, and **webhooks**. Apps can be published to the Zendesk Marketplace. | $19/agent/month (Support Team, billed annually) | 14-day free trial (full Zendesk Suite Professional access with no credit card required); free developer sponsor accounts via developer program |
| **[Freshworks Developer Platform](https://developers.freshworks.com/)** | ~$3.2B Market Cap (Public: FRSH; ~$720M+ Annual Revenue) | Platform for building apps that run inside Freshworks products (Freshdesk, Freshservice, Freshchat, Freshcaller, Freshsales). Provides **FDK (Freshworks Developer Kit)** CLI, App SDK, REST APIs, webhooks, and serverless app support. Apps render in iframes at designated placeholders. | $19/agent/month (Growth plan, billed annually) | 14-day free trial; free developer account for app development & testing in local sandbox |
| **[Postman](https://www.postman.com/)** | ~$3.0B Valuation (Private; Series D valuation $5.6B, secondary estimate ~$3B) | API development environment with Collections, Mock Servers, Monitors, and **Postman CLI**. March 2026 restructure made collection runs unlimited but removed team workspaces from the free plan. | $9/user/month (Solo plan, billed annually) | Free forever plan (single user only, unlimited collection runs, 3 active mock servers, up to 10,000 mock server/monitor calls/month) |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Hoppscotch](https://github.com/hoppscotch/hoppscotch)** | [![Stars](https://img.shields.io/github/stars/hoppscotch/hoppscotch?style=social&color=white)](https://github.com/hoppscotch/hoppscotch/stargazers) | **Open-source API development ecosystem (Postman alternative).** Lightweight, fast web-based API client supporting REST, GraphQL, and WebSockets with collections, environments, and team collaboration. Self-hostable. |
| **[Traefik](https://github.com/traefik/traefik)** | [![Stars](https://img.shields.io/github/stars/traefik/traefik?style=social&color=white)](https://github.com/traefik/traefik/stargazers) | Modern HTTP reverse proxy and cloud-native API gateway that integrates directly with existing infrastructure (Docker, Swarm, Kubernetes, Marathon, Consul, Etcd) and configures itself automatically and dynamically. |
| **[Bruno](https://github.com/usebruno/bruno)** | [![Stars](https://img.shields.io/github/stars/usebruno/bruno?style=social&color=white)](https://github.com/usebruno/bruno/stargazers) | Offline-first, Git-friendly API client. Stores collections as plain text files directly in your repository for clean Git version control; no proprietary cloud sync required. |
| **[Kong Gateway](https://github.com/Kong/kong)** | [![Stars](https://img.shields.io/github/stars/Kong/kong?style=social&color=white)](https://github.com/Kong/kong/stargazers) | Cloud-native, high-performance API gateway and microservice management platform. Acts as the gateway layer for developer platforms handling authentication, rate limiting, and observability. |
| **[Directus](https://github.com/directus/directus)** | [![Stars](https://img.shields.io/github/stars/directus/directus?style=social&color=white)](https://github.com/directus/directus/stargazers) | Open-source data platform that instantly wraps SQL databases with dynamic REST and GraphQL APIs, dynamic SDKs, authentication, and an intuitive developer control panel. |
| **[Backstage](https://github.com/backstage/backstage)** | [![Stars](https://img.shields.io/github/stars/backstage/backstage?style=social&color=white)](https://github.com/backstage/backstage/stargazers) | **CNCF Incubation developer portal framework created by Spotify.** Centralized software catalog for APIs, microservices, and technical documentation ("docs like code" via TechDocs). |
| **[k6](https://github.com/grafana/k6)** | [![Stars](https://img.shields.io/github/stars/grafana/k6?style=social&color=white)](https://github.com/grafana/k6/stargazers) | Modern developer-centric load and API performance testing tool by Grafana Labs. Write performance tests and API contracts using modern JavaScript/TypeScript syntax. |
| **[Swagger UI](https://github.com/swagger-api/swagger-ui)** | [![Stars](https://img.shields.io/github/stars/swagger-api/swagger-ui?style=social&color=white)](https://github.com/swagger-api/swagger-ui/stargazers) | The industry-standard HTML/JS/CSS documentation suite that dynamically generates interactive API reference consoles from OpenAPI (fka Swagger) specifications. |
| **[OpenAPI Generator](https://github.com/OpenAPITools/openapi-generator)** | [![Stars](https://img.shields.io/github/stars/OpenAPITools/openapi-generator?style=social&color=white)](https://github.com/OpenAPITools/openapi-generator/stargazers) | **The most widely used open-source SDK generator.** Generates client libraries, server stubs, documentation, and configuration from OpenAPI 2.0/3.x specs across **50+ languages and frameworks** (Java, Python, TypeScript, Go, Rust, C#, PHP, Ruby, Swift). |
| **[Swagger Codegen](https://github.com/swagger-api/swagger-codegen)** | [![Stars](https://img.shields.io/github/stars/swagger-api/swagger-codegen?style=social&color=white)](https://github.com/swagger-api/swagger-codegen/stargazers) | Open-source code generator that parses OpenAPI specifications into robust client SDKs and server implementation stubs across dozens of programming languages. |
| **[Scalar](https://github.com/scalar/scalar)** | [![Stars](https://img.shields.io/github/stars/scalar/scalar?style=social&color=white)](https://github.com/scalar/scalar/stargazers) | Modern open-source API reference and interactive client generation. Generates developer documentation portals with built-in API testing playgrounds from OpenAPI specs. |
| **[Mockoon](https://github.com/mockoon/mockoon)** | [![Stars](https://img.shields.io/github/stars/mockoon/mockoon?style=social&color=white)](https://github.com/mockoon/mockoon/stargazers) | The easiest and quickest way to run mock REST APIs locally. Features standalone CLI runners for CI/CD pipelines, Docker support, and full templating capabilities. |
| **[Fern](https://github.com/fern-api/fern)** | [![Stars](https://img.shields.io/github/stars/fern-api/fern?style=social&color=white)](https://github.com/fern-api/fern/stargazers) | Open-source toolkit for building developer platforms: generate production-ready, type-safe SDKs (TypeScript, Python, Go, Java) and interactive documentation websites from OpenAPI specifications. |
| **[Spectral](https://github.com/stoplightio/spectral)** | [![Stars](https://img.shields.io/github/stars/stoplightio/spectral?style=social&color=white)](https://github.com/stoplightio/spectral/stargazers) | Flexible JSON/YAML and OpenAPI linter with custom rulesets. Enforces strict API governance, naming standards, and consistency across API definitions before SDK generation. |
| **[Redocly CLI](https://github.com/Redocly/redocly-cli)** | [![Stars](https://img.shields.io/github/stars/Redocly/redocly-cli?style=social&color=white)](https://github.com/Redocly/redocly-cli/stargazers) | Open-source OpenAPI linting, bundling, and multi-file management engine. Enforces enterprise API style guides and compiles multi-file OpenAPI definitions into unified distributions. |
| **[Speakeasy](https://github.com/speakeasy-api/speakeasy)** | [![Stars](https://img.shields.io/github/stars/speakeasy-api/speakeasy?style=social&color=white)](https://github.com/speakeasy-api/speakeasy/stargazers) | **Developer experience-first SDK generator.** Generates idiomatic, type-safe client SDKs from OpenAPI specs with built-in authentication, pagination, automatic retries, and GitHub Actions CI/CD workflows. |

**Frameworks for building custom systems**: Combine **OpenAPI Generator**, **Fern**, or **Speakeasy** for SDK generation from your API specs, **Spectral** or **Redocly CLI** for API linting, **Backstage** for a developer portal, **Kong** or **Traefik** for gateway routing, and **Hoppscotch** or **Bruno** for API testing—creating a fully open-source developer platform stack without per-seat SaaS fees.

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
