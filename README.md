# Carlos Guillermo Ojeda Ovelar

Senior backend engineer in Aachen, Germany. Nine years building production systems, seven of them in C# and .NET.

I work on the parts of a system that have to keep running: service boundaries, data models, authentication, asynchronous processing, and the tests that let you change any of it without holding your breath.

### What I build with

- **Backend .NET** — C#, .NET 8, .NET Core, .NET Framework, ASP.NET Core Web API, ASP.NET MVC, Entity Framework Core, LINQ, Hangfire
- **Architecture** — microservices on Clean Architecture and Domain-Driven Design, CQRS, REST API design, ADRs, RabbitMQ for asynchronous messaging
- **Identity** — OAuth 2.0 and OpenID Connect, with FusionAuth and Keycloak
- **Testing** — TDD with xUnit, NSubstitute and FluentAssertions. Twice I have brought tests into a backend that had none and helped the team keep them
- **Delivery and observability** — GitHub Actions, Jenkins, Azure DevOps, Docker, AWS, Trunk Based Development; New Relic and Grafana in production
- **Data** — SQL Server (stored procedures, functions, views, database-first modelling), PostgreSQL, MongoDB
- **Frontend, when the project needs it** — React 19 and TypeScript (Vite)
- **AI-assisted development** — Claude Code (including my own plugins, skills and slash commands), Codex, and Qwen models run locally through Ollama. I review what they produce before anything lands

### Where that comes from

Roles across Paraguay, the United States, Latin America and Germany, in telecommunications, financial services, insurance, banking, agriculture and travel. Three I would point at:

**journaway GmbH (2024–2026).** German tour operator, one of two senior engineers on the team, promoted from Backend Developer in 2025. Worked on the company-wide authentication and authorization microservice on FusionAuth (OAuth 2.0 / OpenID Connect), and on the booking service as it moved out of the legacy backend into its own microservice. Led New Relic from proof of concept to production; the metrics exposed slow and stalled background jobs, and the follow-up work cut runs from 5–10 minutes to 1–2. Built the GitHub Actions pipelines that moved deployments from weekly manual releases to on demand.

**EDGE (2023).** WhatsApp automation for a telecom operator in 12 countries, in .NET Core and TypeScript. The backend had no tests: I refactored it for testability, covered it with xUnit under TDD, wrote the testing guideline and mentored the seven-person team. Monthly production incidents on those services fell by roughly 35–40%.

**ERP development at Microtech S.A. (2017–2022).** Built the core financial module with the team, which raised end-user productivity by 80% and cut monthly fixed expenses by 10%. Led the payment transactions manager module: SQL Server stored procedures and functions on the critical path, RabbitMQ handling the queues between processing stages.

### Built on my own

**Inventory management platform** for a plastics-industry client (2026), now in production use. Designed and built alone, from requirements to deployment, in about six weeks: 1,140 products and their inbound and outbound flow, for around 20 users in warehouse, administration and purchasing, replacing Excel and an outdated system.

Clean Architecture with light CQRS on .NET and EF Core over PostgreSQL, Keycloak for identity, a React 19 / TypeScript frontend, Docker, deployed to the client's on-premises Debian server. I wrote the project's engineering standards and ADRs and packaged them as a reusable Claude Code plugin.

The repository is private because the code is the client's, but **I can grant read access on request**. If you are evaluating me and want to read real code rather than exercises, ask and I will open it.

### About the public repositories here

Almost everything else I have shipped belongs to an employer, so it is not on this profile. What is public here is practice and study work: Clean Architecture and distributed-systems references I forked to read through, a CRUD app on .NET with an Angular frontend, and small things in Go and JavaScript.

I would rather say that plainly than present a handful of side repositories as a portfolio.

### Currently

Building with AI in the loop every day, and packaging what works into reusable Claude Code plugins, like the engineering standards and ADRs from the inventory platform.

Open to senior backend roles, remote or around Aachen. Available immediately, with an unrestricted German work permit.

### Languages

Spanish and Guaraní (native) · English (C1) · German (B1, taking lessons)

### Reach me

[LinkedIn](https://www.linkedin.com/in/guillermo-ojeda-ovelar-developerpy/)
