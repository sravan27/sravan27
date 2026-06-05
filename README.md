## Sravan Sridhar

AI automation, agentic-systems, and correctness engineer. I turn brittle AI workflows, generated codebases, and correctness-critical systems into working shipped tools — with tests, repros, screenshots, logs, and handoff docs.

**Open this week for paid 24-48 hour sprints.** Best fit: a concrete workflow, agent, internal tool, or a correctness-critical layer (money math, data/sync, access control) that needs to work in production fast. Start from the [live sprint menu](https://sravan27.github.io/money-27-proof/) or email a one-paragraph scope.

### Recent proof (this month)

Found and fixed silent **data-loss bugs in five production databases** — PowerSync, Rocicorp's Zero, InstantDB, ElectricSQL, and Dexie (fixes merged / PRs open) — the kind that return the wrong rows with no error. Packaged the audit as an open-source checker, [silentdrop](https://github.com/sravan27/silentdrop) (`npm i silentdrop`), and applied the same discipline to fintech money-math and a mortgage servicing-copilot core.

Write-ups: [silent data-loss in 5 databases](https://dev.to/sravan27/i-found-silent-data-loss-bugs-in-5-production-databases-this-month-heres-the-open-source-checker-hf1) · [money math done right](https://dev.to/sravan27/your-javascript-app-is-probably-losing-cents-money-math-done-right-254o)

### Fast Sprint Shapes

- **AI workflow rescue:** n8n, Make, Zapier, webhooks, retries, CRM handoffs, observability, and failure maps.
- **Agentic codebase audit:** review AI-generated TypeScript/Python apps, find fragile boundaries, and ship the first cleanup patch.
- **Voice-agent reliability:** Retell/Vapi/GoHighLevel transcript triage, replay cases, failure tags, and implementation fixes.
- **Internal AI tool build:** a small LLM-powered tool with live UI, API glue, eval checks, and runbook.
- **Correctness-critical core:** money math, data/sync query layers, audit trails, access control — built so the silent failures (wrong number, dropped row, leaked record) can't happen, with tests.

### Clickable Proof

- [Live proof homepage](https://sravan27.github.io/money-27-proof/)
- [Voice-agent failure triage tool](https://sravan27.github.io/money-27-proof/voice-agent-failure-triage.html)
- [Landing-page leak finder demo](https://sravan27.github.io/money-27-proof/proof/landing_page_leak_finder_demo.html)
- [Agent cost leak checker](https://sravan27.github.io/money-27-proof/agent-cost-leak-checker.html)
- [Context OS v2.9.0 GitHub Action](https://github.com/sravan27/context-os/releases/tag/v2.9.0)
- [Private repo audit request](https://github.com/sravan27/context-os/issues/new?template=private_audit.yml)

### Featured Repos

- [silentdrop](https://github.com/sravan27/silentdrop): finds silent data-loss bugs (LIKE / case-fold / comparison divergences) in JS database query layers. `npm i silentdrop`.
- [servicing-copilot-core](https://github.com/sravan27/servicing-copilot-core): tested core of a mortgage servicing copilot — integer-cent money math, tamper-evident audit trail, role-scoped PII access.
- [mortgage-money-math](https://github.com/sravan27/mortgage-money-math): money math built so it can't silently lose cents.
- [context-os](https://github.com/sravan27/context-os): CI gate for coding-agent context and cost leaks across Claude Code, Codex, Cursor, and other agentic coding workflows.
- [schema-gateway](https://github.com/sravan27/schema-gateway): schema portability and regression guardrails for structured outputs across OpenAI, Gemini, Anthropic, and Ollama.
- [glasswall](https://github.com/sravan27/glasswall): GitHub-native patch-gap operations for public-fix-to-private-remediation workflows.
- [agent-activity-graph](https://github.com/sravan27/agent-activity-graph): runtime evidence layer for AI agents in enterprise workflows.

### Contact

Email: sravan272001@gmail.com
