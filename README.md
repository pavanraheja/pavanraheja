# Pavan Raheja

**AI Product Manager — I ship agents that act, and the guardrails that make that safe.**

Dubai · **[Work & contact → pavan.blog/work](https://www.pavan.blog/work?utm_source=github&utm_medium=readme&utm_campaign=pavanraheja)** · [LinkedIn](https://linkedin.com/in/pavanraheja)

---

Most AI demos answer. The hard part is letting a system *act* — on real money, real customers, real infrastructure — without a human checking every call. That's the problem I work on.

I run a fleet of production agents across live venues, and the discipline matters more than any single model:

- **60+ candidate strategies evaluated → 4 promoted.** Over 90% were killed by their own test batteries before touching capital.
- **Every candidate declares its promotion criteria *before* seeing results,** then runs shadow → paper → live. No overrides; promotions are gate-driven and audit-logged.
- **Gate on irreversible, not uncertain.** Confidence is the wrong axis — a low-confidence reversible action is safer than a high-confidence irreversible one.
- Author of **RFC #7218**, on preventing catastrophic actions in long-running autonomous agents.

---

### What's here

| Repo | What it is |
|---|---|
| **[alphagrid-orchestrator](https://github.com/pavanraheja/alphagrid-orchestrator)** | The production pattern for safely deploying autonomous systems that act on real resources — risk guardian, kill switch, staged-promotion gates. Start here. |
| **[autonomous-execution-agents](https://github.com/pavanraheja/autonomous-execution-agents)** | The multi-strategy execution fleet the pattern above governs. |
| **[content-research-agent](https://github.com/pavanraheja/content-research-agent)** | Multi-step Claude agents running content research end to end. Said no to RAG — a structured prompt was enough. |
| **[dubai-re-intelligence](https://github.com/pavanraheja/dubai-re-intelligence)** | Flask + Pandas pipeline turning raw Dubai Land Department data into decision intelligence. |
| **[pavan-blog](https://github.com/pavanraheja/pavan-blog)** | My site, including a streaming digital clone built on the Claude API. |

Live systems and production adapters stay private; the reusable patterns are public.

### Building

- **[Glasshouse](https://glasshousedesk.com)** — a transparent research desk. The product is verifiability: strategies are killed by their own falsification batteries, and the copy-service model is non-custodial.
- **[Insight Bay](https://insightbayai.com)** — AI automation for UAE SMEs. First paying customer live.

### Writing

I write at **[pavan.blog](https://pavan.blog)** about what actually breaks in production AI — including [a case study on shipping agents that act without a human](https://pavan.blog/articles/glasshouse-case-study), and [what a year of running production agents taught me about reliability](https://pavan.blog/articles/production-ai-agents-reliability).

---

*Daily stack: Claude Code (hooks, MCP servers, slash commands), Anthropic Agent SDK, tool-use / function-calling, LLM evals. Came up as a software engineer — I build the prototypes myself.*
