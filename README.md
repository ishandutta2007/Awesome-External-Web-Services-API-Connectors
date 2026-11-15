# Awesome-External-Web-Services-API-Connectors

## Top External Web Services & API Connectors Ecosystem

**Curated List of SaaS Platforms & Open-Source GitHub Projects**  
*Focused on iPaaS Orchestration, API Client Workflows & Self-Hosted Connector Gateways*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **External Web Services & API Connectors**. These tools help organizations connect disparate systems—ERPs, CRMs, databases, and SaaS apps—covering everything from commercial low-code automation platforms to open-source frameworks that implement Enterprise Integration Patterns (EIP) in code or provide self-hosted connector gateways for AI agents.

**Examples** include MuleSoft Anypoint, Workato, Boomi, Zapier, Make, Tray.io, Apache Camel, n8n, OpenConnector, and Bruno (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted integration runtimes, open-source API clients, and community-driven connector gateways—ideal for Java teams seeking to avoid per-core licensing, developers wanting Git-native API workflows, and organizations deploying AI agents that need governed access to user applications. The open-source landscape is genuinely mature: **Apache Camel** remains the reference implementation of Enterprise Integration Patterns, **n8n** offers a fair-code visual automation platform with a free Community Edition, and **OpenConnector** provides an open-source connector gateway specifically designed as a Pipedream/Composio alternative for AI agents [citation:1][citation:3][citation:9].

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Company Size (Valuation / Revenue) | Starting Pricing | Free Tier / Trial Limits | Description |
|---------|-----------------------------------|------------------|--------------------------|-------------|
| **[Make](https://www.make.com/)** | $11B parent (Celonis) / ~$100M ARR target (Est. $53M+ rev) | $9/month (Core tier billed annually) | Free forever: 1,000 credits/mo, up to 2 active scenarios, 15-min interval limit | Visual automation platform with credit-based execution, full-text log search, and real-time execution monitoring across 1,500+ apps. |
| **[MuleSoft Anypoint Platform](https://www.mulesoft.com/)** | $6.5B acquisition valuation (Salesforce) / $1B+ ARR | $2,000/month ($24,000/year base commit) | 30-day free trial: full platform access, limited to ~0.1 vCore sandbox runtime and 30-day log/metric retention | Enterprise integration runtime and API management suite with vCore and Mule Credit execution models for mission-critical enterprise workloads. |
| **[Workato](https://www.workato.com/)** | $5.7B valuation / ~$150M ARR | $75/month (Pro self-service, 2,500 credits/mo) | Free forever: 50,000 one-time starter credits with no expiration; Enterprise trial: sales-guided sandbox | Enterprise automation and integration platform featuring recipe-based workflows, Connector SDK, and AI agent copilot orchestration. |
| **[Postman](https://www.postman.com/)** | $5.6B valuation / ~$313M ARR | $14/user/month (Basic billed annually) or $9/month (Solo) | Free forever: 1 user, up to 3 shared collection runs, unlimited local runs, no team workspace access | API development, mocking, testing, and lifecycle management environment standard with Postman CLI and cloud runners. |
| **[Zapier](https://zapier.com/)** | $5.0B valuation / ~$310M ARR | $19.99/month (Professional, billed annually) | Free forever: 100 tasks/month, 2-step Zaps only; 14-day Pro trial: 1,000 tasks with multi-step Zaps | No-code workflow automation connector connecting 7,000+ business applications with Webhooks, branching, and automated logic. |
| **[Boomi](https://www.boomi.com/)** | $4.0B acquisition valuation (Francisco Partners & TPG) / >$500M ARR | $99/month + usage (Pay-As-You-Go) | 30-day free trial: full platform access, restricted to 3 standard connectors and sandbox deployment | Cloud-native enterprise iPaaS with distributed Atom runtime architecture, data mapping, master data hub, and API gateway management. |
| **[Rapid](https://rapidapi.com/)** (formerly RapidAPI) | $1.0B peak valuation (acquired by Nokia) / ~$24M ARR | $10/month (Team plan per additional user; marketplace APIs start $10/mo Pro) | Free forever: 5 free team seats; Public marketplace: basic plan up to 500k requests/mo / 1k req/hr (capped at 10GB bandwidth/mo) | API marketplace and enterprise developer hub for discovering, subscribing to, securing, and testing public and internal APIs. |
| **[Tray.io (Tray.ai)](https://tray.ai/)** | $600M+ valuation / ~$71M ARR | $500/month (Base Pro plan) | 14-day free trial (Tray Academy & evaluation sandbox upon request); no permanent free tier | Low-code enterprise iPaaS and workflow automation platform featuring Merlin AI agent builder and 700+ enterprise connectors. |
| **[Celigo](https://www.celigo.com/)** | Private (~$30M-$72M funded) / ~$95M ARR | $600/month (~$7,200/year Standard base tier) | Free forever: 1 active production flow, 2 endpoints, no SSO; 30-day full platform trial | iPaaS specialized in ERP, NetSuite, CRM, and eCommerce integrations with pre-built smart business integration apps. |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Apache Camel](https://github.com/apache/camel)** | [![Stars](https://img.shields.io/github/stars/apache/camel?style=social&color=white)](https://github.com/apache/camel/stargazers) | **The most widely used open-source integration framework and reference implementation of Enterprise Integration Patterns.** Apache-2.0, Java/JVM. **~300 components** covering databases, messaging (Kafka, JMS, AMQP), cloud services, and SaaS apps. Routes in **Java, YAML, or XML DSL**; visual editor via Kaoto. Runs standalone, embedded in Spring Boot/Quarkus, or as native image. **Trade-offs**: no bundled API management, hosting, or commercial support—you run and operate it yourself. **Best for Java teams wanting the widest connectivity and pattern coverage** without per-core licensing [citation:2][citation:9][citation:15]. |
| **[n8n](https://github.com/n8n-io/n8n)** | [![Stars](https://img.shields.io/github/stars/n8n-io/n8n?style=social&color=white)](https://github.com/n8n-io/n8n/stargazers) | **Fair-code workflow automation with 400+ integrations.** **Community edition is free forever and self-hosted**, including almost the complete feature set. **Registered Community edition** (free with email) unlocks folders, debug in editor, and custom execution data. **Business/Enterprise plans** add SSO, external secrets, log streaming, and Git version control. **Trade-off**: Community edition excludes SSO, sharing, and projects—those require paid tiers [citation:3][citation:10]. **Best for teams wanting a proven visual automation platform** without per-task fees for basic use. |
| **[OpenConnector](https://github.com/oomol-lab/open-connector)** | [![Stars](https://img.shields.io/github/stars/oomol-lab/open-connector?style=social&color=white)](https://github.com/oomol-lab/open-connector/stargazers) | **Open-source connector gateway for AI agents—a direct Pipedream/Composio alternative.** **1,000+ providers and 10,000+ pre-built Actions** in a shared catalog. **Self-host with Docker or Node.js**—you manage storage and OAuth apps. **Connector SDK** (TypeScript HTTP client), **oo CLI** for local Agent relaying, **MCP** for Agent hosts, and **HTTP/OpenAPI** for custom clients. **Runtime controls**: credential/scope/schema/policy retention, action allow/block policies, and redacted logs. **Best for teams building AI agent products** that need governed access to user applications without handing credentials to the Agent process [citation:1][citation:8]. |
| **[Hoppscotch](https://github.com/hoppscotch/hoppscotch)** | [![Stars](https://img.shields.io/github/stars/hoppscotch/hoppscotch?style=social&color=white)](https://github.com/hoppscotch/hoppscotch/stargazers) | **Open-source API development ecosystem with web, desktop, and CLI clients.** **Self-host on your own server** and use it with your team. Cross-platform (Web, Mac, Windows, Linux, CLI). **Keyboard-first design** with minimalist UI. **Best for teams wanting a self-hosted Postman alternative** with broad protocol support and no cloud dependency [citation:4][citation:11]. |
| **[Bruno](https://github.com/usebruno/bruno)** | [![Stars](https://img.shields.io/github/stars/usebruno/bruno?style=social&color=white)](https://github.com/usebruno/bruno/stargazers) | **Git-friendly, offline-first API client built for developers.** **Collections stored as plain-text YAML files**—review API changes like code. **No account required**—work locally without cloud dependency. **Native Git versioning** for API collections. **Best for teams wanting API workflows under version control** without proprietary cloud lock-in [citation:5][citation:12]. |

### Additional Strong Open-Source Options

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Spring Integration](https://github.com/spring-projects/spring-integration)** | [![Stars](https://img.shields.io/github/stars/spring-projects/spring-integration?style=social&color=white)](https://github.com/spring-projects/spring-integration/stargazers) | **Enterprise Integration Patterns inside the Spring ecosystem.** Lightweight messaging framework extending Spring's programming model with EIP components—channels, routers, transformers, and adapters. **Best when integrations live inside Spring Boot applications** and you want to stay within the Spring programming model. **Trade-off**: a library, not a product—no visual designer or managed hosting. |
| **[KrakenD](https://github.com/krakend/krakend-ce)** | [![Stars](https://img.shields.io/github/stars/krakend/krakend-ce?style=social&color=white)](https://github.com/krakend/krakend-ce/stargazers) | **Ultra-high performance API Gateway (Community Edition).** **+70K reqs/s on a single instance**, under 50MB memory with +1000 concurrent. **Stateless design** for linear scalability. **Content aggregation, transformation (XML↔JSON), security (OAuth, JWT), and multi-layer rate limiting**. **Best for teams needing a lightweight, high-performance API gateway** to front microservices or external services [citation:14]. |

**Frameworks for building custom systems**: Choose **Apache Camel** for the widest connectivity and EIP patterns in Java , **n8n** for a proven visual automation platform with a free Community Edition , or **OpenConnector** for AI-agent connector governance with 10,000+ pre-built Actions —all without per-core or per-task commercial licensing that compounds at scale.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- External API connectors and integration platforms handle credentials and business data flowing between systems; enforce least-privilege OAuth scopes, secret rotation, and audit logging for all connector activity.
- **Open-source integration tooling has different trade-offs across projects.** **Apache Camel** is the most mature with ~300 components, but requires JVM expertise and self-operation . **n8n's Community Edition is free forever** but **excludes SSO, sharing, and projects**—those require Business/Enterprise plans . **OpenConnector** is purpose-built for AI agents with runtime policy controls, but is newer and OAuth app management is your responsibility when self-hosting . **Hoppscotch and Bruno** solve API client needs, not integration orchestration—choose based on whether you need to *build* connections or *test* APIs . **Validate whether you need visual automation (n8n), code-first EIP (Camel), AI-agent governance (OpenConnector), or Git-native API testing (Bruno)** before committing.

---

**Made for integration engineers, platform teams, and developers building external connectivity.**  
Let's make external web services and API connectors more open, governed, and developer-friendly.
