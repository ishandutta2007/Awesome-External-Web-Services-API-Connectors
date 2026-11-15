# Awesome-External-Web-Services-API-Connectors

# Top External Web Services & API Connectors Ecosystem

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

| Product | Description | Pricing (Starting) | Free Tier / Trial Limits |
|---------|-------------|-------------------|--------------------------|
| **[MuleSoft Anypoint Platform](https://www.mulesoft.com/)** | Enterprise iPaaS and API management standard. vCore-based pricing with typical contract minimums in the mid-five to low-six figures annually. Median contract ~$68,695/year (Vendr). Implementation services typically 20–40% of first-year software cost. | Quote-only (median ~$68,695/year) | 30-day free trial available |
| **[Workato](https://www.workato.com/)** | Enterprise automation platform with recipe-based workflows and a Connector SDK. Positioned for large-scale enterprise automation with AI capabilities. | Free: $0 (50,000 one-time credits); Pro: $75/month (2,500 credits/month) | Free: 50,000 one-time credits that never expire |
| **[Boomi](https://www.boomi.com/)** | Cloud-native iPaaS with Atom-based architecture. API Management sold separately in four editions. Pay-As-You-Go option: $99/month + usage with no contract. | Pay-As-You-Go: $99/month + usage; Editions: quote-only | 30-day free trial ($0, full platform access) |
| **[Zapier](https://zapier.com/)** | No-code automation connecting 7,000+ apps. Free tier limited to two-step Zaps. 14-day Pro trial with 1,000 tasks on new accounts. | Professional: $19.99/month (750 tasks) | Free: 100 tasks/month, 2-step Zaps only; 14-day Pro trial: 1,000 tasks |
| **[Make](https://www.make.com/)** | Visual automation platform with credits as the billing unit. Unlimited users on all plans. Real-time execution monitoring and full-text log search. | Credit-based tiers (see vendor pricing) | Free tier available with limited credits |
| **[Tray.io (Tray.ai)](https://tray.ai/)** | Enterprise low-code iPaaS with 700+ connectors and AI agent capabilities. Rebranded to Tray.ai in 2024 with Merlin Agent Builder. | Quote-only (Pro tier reported from ~$500/month) | Free trial available via sales |
| **[Celigo](https://www.celigo.com/)** | iPaaS with strong NetSuite and ERP focus. Flow-based pricing; median contract ~$14,787/year. Pre-built apps priced separately. | Flow-based quote (median ~$14,787/year) | Free plan: 2 endpoints, 1 flow, no SSO (no expiration); 30-day trial: unlimited everything |
| **[Postman](https://www.postman.com/)** | API development environment with Collections, Mock Servers, Monitors, and CLI. March 2026 restructure made collection runs unlimited but removed team workspaces from free plan. | Solo: $9/month; Team: $19/user/month | Free: 1 user only, unlimited collection runs, no team workspace |
| **[RapidAPI](https://rapidapi.com/)** | API marketplace and hub for discovering, testing, and connecting to thousands of public APIs. | Quote-only (marketplace listing and enterprise hub pricing) | Free to browse and test APIs; paid API subscriptions vary |

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
