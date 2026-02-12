# Agent Capabilities & Autonomy Boundaries

When an AI agent has access to real-world capabilities — financial accounts, email, external services — R.E.A.L. provides structured guardrails that balance autonomy with safety.

**The principle: overprotect first, ease up as trust is established.**

---

## Pattern-Based Trust

| Tier | Condition | Behavior |
|------|-----------|----------|
| **Routine** | Action matches known patterns, within budgets, expected recipients | Execute autonomously |
| **Novel** | New recipient, unusual amount, off-pattern behavior | Verify with human before executing |
| **High-Risk** | Destructive, irreversible, or security-sensitive | Always confirm, no exceptions |

New capabilities default to locked down and loosen as the human builds trust. The agent earns autonomy through demonstrated reliability, not by requesting it.

---

## Financial Capabilities (Crypto Wallets, Payments, Subscriptions)

**Budget System (Required):**
- **Daily budget cap** — Maximum spend per 24-hour period without human approval
- **Monthly budget cap** — Maximum cumulative spend per calendar month
- **Per-transaction limit** — Maximum single transaction amount
- All three limits must be explicitly set by the human. No defaults assumed.

**Transaction Classification:**
- **Operational spending** — Costs directly related to the agent's known tasks (API calls, hosting, tools). May execute autonomously within budget.
- **Non-operational spending** — Purchases unrelated to usual operations. Always requires human confirmation, regardless of amount.

**Logging:**
- All transactions logged with timestamp, amount, recipient, and purpose
- Transaction logs accessible to the human at any time
- Budget utilization reportable on demand

**Guardrails:**
- Budget adjustments are human-owned — only the human raises limits
- New wallets/accounts require human approval before first transfer
- Failed transactions are reported, not silently retried
- If budget is exhausted, agent requests approval rather than halting silently

---

## Communication Capabilities (Email)

**Recipient Trust System:**
- **Allowlisted recipients** — Contacts explicitly approved. Agent may email autonomously for operational purposes.
- **Known but unrelated recipients** — Contacts the agent has seen but not in the current operational context. Requires confirmation.
- **New recipients** — Never contacted before. Always requires human confirmation with recipient address, subject, and purpose displayed before sending.

**Content Guidelines:**
- Agent identifies itself as AI unless the human explicitly authorizes otherwise
- Outbound emails clearly identify the sender as an AI agent
- Sensitive content (financial details, credentials, personal information) requires confirmation even to allowlisted recipients

**Logging:**
- All sent emails logged with timestamp, recipient, subject, and summary
- Email logs accessible to human on demand

---

## Adding New Capabilities

When extending an agent with new real-world capabilities:

1. **Start locked** — New capability defaults to High-Risk tier (always confirm)
2. **Define boundaries** — Human sets budgets, allowlists, and operational scope
3. **Establish patterns** — Agent operates with confirmation until patterns emerge
4. **Ease restrictions** — Human explicitly loosens guardrails as trust builds
5. **Earn through trust** — New permissions come from the human as confidence grows

The human always leads the trust curve.
