# Welcome to OpenAEO

**OpenAEO** is an open-source initiative dedicated to building the infrastructure for **Answer Engine Optimization (AEO)**.

As the internet shifts from traditional search engines (Google) to Answer Engines (Perplexity, ChatGPT, Claude), traditional SEO metrics are becoming obsolete. If your startup, documentation, or product isn't explicitly cited in an AI's generated answer, you are invisible to the next generation of users.

We build tools that help developers, founders, and marketers monitor, analyze, and optimize their visibility within Large Language Models (LLMs).

## 🌟 Flagship Project

### [open-aeo/open-aeo](https://github.com/open-aeo/open-aeo)
Our core engine. A headless, local Model Context Protocol (MCP) server that connects Claude Desktop directly to live Answer Engine data.
* **Live Citation Checking:** See if you are cited for high-value queries.
* **Hexagonal Architecture:** Built with pure Ports & Adapters for extreme extensibility.
* **Local-First:** Your competitive data is stored locally in JSON, never on our servers.

## 🛠️ The Architecture
We believe in the "Open Core" model. All our tools are built using strict Domain-Driven Design and Hexagonal Architecture, ensuring they can be run locally via CLI/MCP today, and easily scaled to cloud infrastructure tomorrow.

## 🤝 Get Involved
The Answer Engine era is just beginning, and the tooling is still being invented. We are actively looking for contributors to help build:
* **New Adapters:** OpenAI SearchGPT, Google AI Overviews, Firecrawl web scraping.
* **Data Pipelines:** PostgreSQL storage adapters, historical trend diffing.
* **Actionable Insights:** LLM-driven PR outreach generation for missed citations.

[Read our Contributing Guidelines](https://github.com/open-aeo/open-aeo/blob/main/CONTRIBUTING.md) to get started.

---
*OpenAEO is an open-source project. MIT Licensed.*
