<h1 align="center">Awesome A2A</h1>

<p align="center">
  <strong>A curated list of awesome Agent-to-Agent (A2A) compatible agents, tools, and resources.</strong>
</p>

<p align="center">
  <a href="https://awesome.re"><img src="https://awesome.re/badge.svg" alt="Awesome"/></a>
  <a href="https://github.com/inference-gateway/awesome-a2a/blob/main/LICENSE"><img src="https://img.shields.io/github/license/inference-gateway/awesome-a2a?color=blue&style=flat-square" alt="License"/></a>
  <a href="https://github.com/inference-gateway/awesome-a2a/stargazers"><img src="https://img.shields.io/github/stars/inference-gateway/awesome-a2a?color=blue&style=flat-square" alt="Stars"/></a>
  <a href="https://github.com/inference-gateway/awesome-a2a/network/members"><img src="https://img.shields.io/github/forks/inference-gateway/awesome-a2a?color=blue&style=flat-square" alt="Forks"/></a>
  <a href="https://github.com/inference-gateway/awesome-a2a/graphs/contributors"><img src="https://img.shields.io/github/contributors/inference-gateway/awesome-a2a?color=blue&style=flat-square" alt="Contributors"/></a>
  <a href="https://github.com/inference-gateway/awesome-a2a/commits/main"><img src="https://img.shields.io/github/last-commit/inference-gateway/awesome-a2a?color=blue&style=flat-square" alt="Last commit"/></a>
</p>

The [Agent-to-Agent (A2A) protocol](https://google-a2a.github.io/A2A/latest/) enables seamless communication and coordination between AI agents. This list showcases tested, working A2A-compatible agents, tools, libraries, and resources.

> [!TIP]
> **New to A2A?** Start with the [Agent Development Kit (ADK)](https://github.com/inference-gateway/adk) and ship your first A2A-compatible agent in minutes.

## ⚡ Featured

- **[Agent Development Kit (ADK)](https://github.com/inference-gateway/adk)** - The fastest way to build A2A agents in Go (Rust and TypeScript flavors available too).
- **[Agent Definition Language (ADL)](https://github.com/inference-gateway/adl)** - Declare your agent in YAML; scaffold Go, Rust, or TypeScript with one CLI command.
- **[Inference Gateway](https://github.com/inference-gateway/inference-gateway)** - Drop-in proxy that connects any A2A agent to any LLM.
- **[A2A Protocol Specification](https://google-a2a.github.io/A2A/latest/)** - The official spec - start here to understand the protocol.

_8 agents · 12 tools & libraries · 3 docs · 1 example · Last updated 2026-05-25_

## 📑 Contents

- [⚡ Featured](#-featured)
- [🤖 Agents](#-agents)
  - [🌐 Browser & Web](#-browser--web)
  - [📊 DevOps & Observability](#-devops--observability)
  - [🔧 Development & Utilities](#-development--utilities)
  - [📚 Documentation](#-documentation)
  - [💰 Finance & Investment](#-finance--investment)
  - [📅 Productivity & Calendar](#-productivity--calendar)
  - [🔄 Workflow Automation](#-workflow-automation)
- [🛠️ Tools & Libraries](#%EF%B8%8F-tools--libraries)
  - [🏗️ Frameworks & SDKs](#%EF%B8%8F-frameworks--sdks)
  - [🔌 Integration Platforms](#-integration-platforms)
  - [🚀 Deployment & Operations](#-deployment--operations)
  - [🐛 Debugging & Testing](#-debugging--testing)
  - [📦 Registries, Catalogs & Schemas](#-registries-catalogs--schemas)
- [📖 Documentation & Resources](#-documentation--resources)
  - [Official Documentation](#official-documentation)
  - [Getting Started](#getting-started)
- [🎓 Examples & Tutorials](#-examples--tutorials)
- [🤝 Contributing](#-contributing)

> [!NOTE]
> Each entry is tagged with its primary language and license. `⭐ Featured` marks curator picks; `🆕 New` marks entries added in the last ~90 days.

## 🤖 Agents

### 🌐 Browser & Web

- **[Browser Agent](https://github.com/inference-gateway/browser-agent)** `Go` `Apache-2.0` - A2A agent server for browser automation and web testing using Playwright.

### 📊 DevOps & Observability

- **[Grafana Agent](https://github.com/inference-gateway/grafana-agent)** `Go` `Apache-2.0` - A2A agent server for automating Grafana dashboard creation, querying, and management.

### 🔧 Development & Utilities

- **[Mock Agent](https://github.com/inference-gateway/mock-agent)** `Go` `Apache-2.0` - A2A agent that returns canned responses - useful for testing client integrations and CI flows without a real backend.
- **[OpenAgents](https://github.com/openagents-org/openagents)** `Python` `Apache-2.0` - Open-source platform for building AI agent networks with native A2A protocol support alongside MCP, WebSocket, gRPC, and HTTP.

### 📚 Documentation

- **[Documentation Agent](https://github.com/inference-gateway/documentation-agent)** `Go` `Apache-2.0` - A2A-compatible agent for libraries and code documentation, using Context7 as the underlying data source.

### 💰 Finance & Investment

- **[GitDealFlow Signal Agent](https://github.com/kindrat86/mcp-deal-flow-signal)** `JavaScript` `MIT` - A2A agent for VC deal-flow and startup discovery. Surfaces commit velocity, contributor growth, and breakout signals across 19 sectors from public GitHub activity. Five read-only skills, no auth, weekly refresh. AgentCard at [signals.gitdealflow.com](https://signals.gitdealflow.com/.well-known/agent-card.json).

### 📅 Productivity & Calendar

- **[Google Calendar Agent](https://github.com/inference-gateway/google-calendar-agent)** `Go` `Apache-2.0` `⭐ Featured` - A2A-compatible agent for Google Calendar with full CRUD operations and event management capabilities.

### 🔄 Workflow Automation

- **[n8n Agent](https://github.com/inference-gateway/n8n-agent)** `Go` `Apache-2.0` - A2A agent server specialized in generating and automating n8n workflows.

<p align="right"><a href="#-contents">↑ Back to top</a></p>

## 🛠️ Tools & Libraries

### 🏗️ Frameworks & SDKs

- **[Agent Development Kit (ADK)](https://github.com/inference-gateway/adk)** `Go` `Apache-2.0` `⭐ Featured` - Complete framework for building A2A-compatible agents in Go with schema-driven development.
- **[Rust ADK](https://github.com/inference-gateway/rust-adk)** `Rust` `Apache-2.0` - Agent Development Kit for building A2A-compatible agents in Rust.
- **[TypeScript ADK](https://github.com/inference-gateway/typescript-adk)** `TypeScript` - Agent Development Kit for building A2A-compatible agents in TypeScript.
- **[Agent Definition Language (ADL)](https://github.com/inference-gateway/adl)** `Apache-2.0` - Declarative YAML manifest format for defining AI agents, their skills, capabilities, and tools. Generates consistent, enterprise-ready code from a single source of truth.
- **[ADL CLI](https://github.com/inference-gateway/adl-cli)** `Go` `Apache-2.0` - Command-line tool to scaffold and manage enterprise-ready A2A agents from ADL manifests. Generates Go, Rust, and TypeScript projects.
- **[systemprompt-template](https://github.com/systempromptio/systemprompt-template)** `Rust` `BSL-1.1` - Production-grade Rust runtime for hosting and governing MCP servers with A2A orchestration. Built-in 6-tier RBAC, secret detection (35+ patterns), rate limiting, audit logging, OAuth 2.0 + WebAuthn. Single binary (~50 MB), PostgreSQL only - no Kubernetes, no Redis.

### 🔌 Integration Platforms

- **[Inference Gateway](https://github.com/inference-gateway/inference-gateway)** `Go` `Apache-2.0` `⭐ Featured` - Proxy server with built-in A2A integration support for connecting agents to language models.

### 🚀 Deployment & Operations

- **[Operator](https://github.com/inference-gateway/operator)** `Go` `Apache-2.0` - Kubernetes Operator for managing the lifecycle of the Inference Gateway and related A2A components - deployment, configuration, and scaling.

### 🐛 Debugging & Testing

- **[A2A Debugger](https://github.com/inference-gateway/a2a-debugger)** `Go` `Apache-2.0` - The ultimate A2A agents troubleshooter - CLI utilities for inspecting, replaying, and testing agent traffic.

### 📦 Registries, Catalogs & Schemas

- **[Registry](https://github.com/inference-gateway/registry)** `TypeScript` `Apache-2.0` - Web registry for hosting and discovering A2A agents built with the Inference Gateway ADK family.
- **[Skills Catalog](https://github.com/inference-gateway/skills)** `Apache-2.0` - Curated catalog of Agent Skills for the Inference Gateway ecosystem - reusable capabilities that A2A agents can load at runtime.
- **[Schemas](https://github.com/inference-gateway/schemas)** `JavaScript` `Apache-2.0` - Shared OpenAPI/JSON Schemas, including A2A, MCP, and other protocol definitions consumed by SDKs and tooling across the ecosystem.

<p align="right"><a href="#-contents">↑ Back to top</a></p>

## 📖 Documentation & Resources

### Official Documentation

- **[A2A Protocol Specification](https://google-a2a.github.io/A2A/latest/)** `⭐ Featured` - The official A2A protocol documentation and specification.
- **[Inference Gateway Documentation](https://docs.inference-gateway.com)** - Comprehensive guides for using A2A agents with the Inference Gateway.

### Getting Started

- **[A2A ADK Documentation](https://github.com/inference-gateway/adk#readme)** - Complete guide to building agents with the Agent Development Kit.

<p align="right"><a href="#-contents">↑ Back to top</a></p>

## 🎓 Examples & Tutorials

### Reference Implementations

- **[Google Calendar Agent Example](https://github.com/inference-gateway/google-calendar-agent/tree/main/example)** `Go` - Complete example showing how to integrate and use the Google Calendar agent.

<p align="right"><a href="#-contents">↑ Back to top</a></p>

## 🤝 Contributing

Contributions are welcome! Adding a new agent or tool takes three steps:

1. **Fork** this repository.
2. **Add your entry** to the right section, following the format below.
3. **Open a pull request** with a brief explanation of what you're adding.

**Entry format:**

```markdown
- **[Name](https://github.com/owner/repo)** `Language` `License` - Brief description of what it does and its key capabilities.
```

> [!IMPORTANT]
> **Quality standards.** Submissions should:
> - ✅ Follow the A2A protocol specification
> - ✅ Include comprehensive documentation
> - ✅ Ship working examples or demos
> - ✅ Be actively maintained
> - ✅ Handle errors properly
> - ✅ Follow security best practices

<p align="right"><a href="#-contents">↑ Back to top</a></p>

---

<p align="center">
  <strong>Interested in building A2A agents?</strong><br>
  Start with the <a href="https://github.com/inference-gateway/adk">Agent Development Kit</a> and join our growing ecosystem!
</p>
