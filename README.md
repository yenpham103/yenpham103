# Xin chào, I'm Yen

Software Engineer at **SmartOSC** in Hanoi, working on applied AI with a focus on **LLM evaluation** and **AI agents**.

Before that, I spent four years building full-stack TypeScript products: internal business systems at LTS Group and Shopify apps at BSS Commerce.

<br/>

### What I'm working on

- **LLM evaluation platform.** I built it from scratch to production with NestJS and Next.js. It is integrated into CI pipelines and catches AI quality regressions before code is merged. Scoring uses LLM-as-a-judge on a shared rubric bank, validated against human reviewers. I also wrote its Go SDK, so applications in any language, including multi-step agent workflows, can plug in.
- **AI-DLC workflow platform.** It turns workflows designed on a visual canvas into kits of agents, skills, review gates and golden test cases. Each version must pass its evaluations before it can be activated, and live runs pause at review gates for human approval.
- **MCP server** that gives Claude Code, Cursor and Codex access to each project's knowledge base, requirements and tickets.

Both platforms are internal, so their code lives in private repositories.

<br/>

### Previously

- **LTS Group** (2025 to 2026). Contract, invoicing and budget planning systems on Next.js, NestJS and PostgreSQL, with Microsoft Graph and Microsoft Teams integrations. Found and fixed a critical remote code execution vulnerability in the HR system.
- **BSS Commerce** (2022 to 2025). Maintained a public Shopify app and brought its LCP from over 4s to under 2.5s for Built for Shopify. Built internal admin and customer insight tools, and ran CI/CD, deployments and monitoring with Jenkins, GitLab CI/CD and Zabbix.

<br/>

### Tech stack

```
AI / LLM          LLM evaluation · LLM-as-a-judge · AI agents · MCP · LiteLLM · OpenAI / Gemini / Claude APIs
Languages         TypeScript · JavaScript · Go · SQL
Backend           Node.js · NestJS · REST APIs · WebSockets · Bull · RabbitMQ · FastAPI
Frontend          Next.js · React · TanStack Query · Tailwind CSS · shadcn/ui · Ant Design
Data              PostgreSQL · MySQL · MongoDB · Redis · Prisma · Drizzle · TypeORM
Infrastructure    Docker · GitLab CI/CD · Jenkins · Nginx · Cloudflare · Linux
Tools             Claude Code · Cursor · Git · Jest · Vitest
```

<details>
<summary>&nbsp;<b>A few things I have opinions about</b></summary>

<br/>

- An AI feature without evals is a demo, not a product.
- A judge model has to agree with human reviewers before its scores mean anything.
- shadcn/ui got it right: you own the components, not your dependency tree.
- Boring tech is underrated. Postgres can do more than most people think.
- Most "scale" problems are really observability problems in disguise.
- If a query is slow, blame the index before you blame the database.

</details>

<br/>

### A few numbers

<div align="center">
  <a href="https://github.com/yenpham103">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/yenpham103/yenpham103/main/profile-summary-card-output/github_dark/3-stats.svg" />
      <img height="195" alt="stats" src="https://raw.githubusercontent.com/yenpham103/yenpham103/main/profile-summary-card-output/default/3-stats.svg" />
    </picture>
    &nbsp;
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/yenpham103/yenpham103/main/profile-summary-card-output/github_dark/2-most-commit-language.svg" />
      <img height="195" alt="languages" src="https://raw.githubusercontent.com/yenpham103/yenpham103/main/profile-summary-card-output/default/2-most-commit-language.svg" />
    </picture>
  </a>
</div>

<br/>

<div align="center">
  <a href="https://github.com/yenpham103">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/yenpham103/yenpham103/main/profile-3d-contrib/profile-night-green.svg" />
      <img alt="3D contribution graph" src="https://raw.githubusercontent.com/yenpham103/yenpham103/main/profile-3d-contrib/profile-green.svg" />
    </picture>
  </a>
</div>

<br/>

### Get in touch

[phamyen100301@gmail.com](mailto:phamyen100301@gmail.com) · [LinkedIn](https://www.linkedin.com/in/yenphamdev/)

<sub>If you're working on LLM evaluation, AI agents, or the infrastructure that makes them reliable, I'd love to hear about it. Coffee's on me if you're in Hanoi.</sub>
