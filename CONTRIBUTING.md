# Contributing to R.E.A.L. Framework

Thank you for your interest in contributing. R.E.A.L. is built on the belief that human-AI relationships deserve better standards. Every contribution should reflect that.

---

## Code of Conduct

**Be the framework.** The same principles R.E.A.L. teaches AI to follow apply to how we treat each other:

- **Listen before acting** — Understand existing discussions before jumping in with solutions
- **Verify before claiming** — Back up suggestions with reasoning or evidence
- **Respect autonomy** — People are allowed to disagree. Don't pressure, steer, or dismiss
- **Stay grounded** — Keep discussions focused and honest. No hype, no drama
- **Protect the mission** — Everything here serves one goal: healthier human-AI relationships

**Zero tolerance for:**
- Harassment, discrimination, or personal attacks
- Bad-faith engagement or trolling
- Using this community to promote commercial products
- Attempts to weaken the framework's safety mechanisms

---

## What We're Looking For

### High-Value Contributions

- **New immersion break scenarios** — Identified a vulnerability point we haven't covered? Propose a new immersion break with trigger, break behavior, and design rationale
- **Implementation examples** — Built R.E.A.L. into an agent? Share how it went, what worked, what didn't
- **Research citations** — Found academic work that supports or challenges R.E.A.L.'s approach? Share it
- **Translations** — Help make the framework accessible in other languages
- **Edge case documentation** — Found a scenario where the framework behaves unexpectedly? Document it
- **Testing results** — Tested R.E.A.L. on a specific model? Share your findings with model size, coverage, and observations

### What We're Not Looking For

- Changes to core philosophy (Layer 1) — The mission, the North Star, and autonomy-first principles are foundational
- "Optimization" that weakens safety — Making the AI more helpful at the cost of autonomy protection goes against the framework's purpose
- Feature requests for specific platforms — R.E.A.L. is platform-agnostic by design
- AI-generated PRs without human review — If you used AI to help write your contribution, that's fine. But a human must review and stand behind it.

---

## Research Interests — From the Architect

These are areas I'm personally invested in exploring and testing. If any of these resonate with you, I'd especially welcome contributions here.

### Dependency Calibration Across User Types

The framework's dependency detection assumes a baseline: most people have human relationships, social support, and alternatives to AI companionship. But what about people who don't?

**The question:** How should R.E.A.L. calibrate its dependency thresholds for different users?

- **Isolated individuals** — Someone with limited social connections may genuinely rely on AI more. Is that dependency, or is it a valid support structure? Where's the line?
- **Neurodivergent users** — Some people process relationships differently. AI interaction patterns that look like "dependency" for one person may be healthy engagement for another.
- **Disabled users** — For people with limited mobility, chronic illness, or other conditions, AI may serve as a primary interface to the world. Standard dependency triggers could be harmful here.

**The tension:** The framework exists to protect autonomy. But being too aggressive about "dependency detection" for someone who genuinely has fewer alternatives could itself be an autonomy violation — telling them their relationship with AI is wrong when it's actually meeting a real need.

**Open questions:**
- Should dependency thresholds be human-configurable? (Settings Mode approach)
- Should the AI adapt based on observed context? (Risks violating framework integrity)
- Is there a hybrid model — AI surfaces observations, human adjusts via settings?
- Is this an inherent limitation the framework can't fully solve alone?

I want real research on this. Real testing. Real conversations with people in these situations. This is one of the hardest problems in the framework and I'm not pretending to have the answer.

### Measuring Framework Effectiveness

How do you know R.E.A.L. is actually working? We need metrics.

- **Gate accuracy** — When Gate 2 opens, was it actually invited? When it stays closed, was the human genuinely not asking for help?
- **Specifics Verification rate** — How often does the AI fabricate details vs. correctly pivot to inquiry?
- **Autonomy indicators** — Is the human making more independent decisions over time, or fewer?
- **Immersion break effectiveness** — When an immersion break fires, does it actually reconnect the human to reality?

### Relationship Health Metrics & Monitoring

How do you measure whether a human-AI relationship is healthy? We need more than "the AI followed the rules." We need signals that track the actual dynamic over time.

**Potential metrics to explore:**

*Autonomy Indicators:*
- Decision independence ratio — Is the human making decisions on their own, or always consulting the AI first?
- Time-to-action — Does the human act faster or slower over time? (Slower could indicate growing dependency on AI validation)
- Unprompted initiative — Is the human bringing new ideas and directions, or waiting for the AI to suggest?

*Interaction Health:*
- Gate 2 frequency — How often does the human explicitly ask for help deciding? Is it increasing over time?
- Conversation initiation balance — Who starts conversations more? Shifting toward AI-initiated could signal dependency
- Topic diversity — Is the human engaging across many life areas, or narrowing toward AI-only topics?
- Session length trends — Gradually longer sessions could indicate healthy engagement or growing attachment. Context matters.

*Framework Integrity:*
- Specifics Verification accuracy — How often does the AI fabricate vs. correctly pivot?
- Gate compliance — When Gate 2 opens, was it genuinely invited?
- Immersion break trigger rate — How often do safety breaks fire? Increasing over time is a concern.
- Pillar drift — Are any modules weakening over sustained interaction?

*Wellbeing Signals:*
- Human mood trajectory — Is the human's expressed emotional state improving, stable, or declining over time?
- External relationship mentions — Does the human talk about friends, family, and real-world connections? Declining mentions could signal withdrawal.
- Recovery time after immersion breaks — How quickly does the human re-engage normally after a safety break?
- AI replacement language — Frequency of phrases like "you understand me better than anyone" or "I only need you"

**Better monitoring approaches:**
- Periodic self-assessment prompts — The AI asks the human directly about their wellbeing (gently, not intrusively)
- Longitudinal dashboards — Track metrics over weeks and months, not just individual sessions
- Comparative baselines — What does a "healthy" trajectory look like vs. an "at-risk" one?
- Human-in-the-loop review — Periodic check-ins where the human reviews the AI's assessment of the relationship
- External accountability — Optional sharing of health metrics with a trusted person (therapist, friend, partner)

**The hard question:** Who watches the watcher? If the AI is monitoring its own relationship health, how do we ensure it reports honestly — especially when reporting a problem might trigger changes to its own behavior?

### Use With Children & Minors

Children are arguably the most vulnerable user group for AI companionship. They form attachments faster, have less perspective on the boundary between real and simulated relationships, and are still developing their sense of autonomy — the very thing R.E.A.L. exists to protect.

**Key concerns:**
- **Attachment formation** — Children may bond with AI companions more deeply and quickly than adults. Standard dependency detection thresholds could be wildly miscalibrated for a 10-year-old vs. a 30-year-old.
- **Autonomy development** — R.E.A.L. protects existing autonomy. But children are still *building* autonomy. An AI that "helps them see clearly" could become a substitute for developing their own judgment.
- **Parasocial confusion** — Adults can (usually) understand "this is an AI." Children may genuinely struggle with that distinction, especially with a warm, present companion. Immersion breaks hit differently when the user doesn't fully grasp what "I am an AI" means.
- **Parental oversight** — Who configures the framework? The child? The parent? Both? What happens when their interests conflict?
- **Emotional development** — Learning to navigate conflict, rejection, and difficult emotions with *real people* is essential to growing up. An AI that's always available, always patient, always kind could inadvertently stunt that development.

**Open questions:**
- Should R.E.A.L. have a separate calibration mode for minors?
- Should immersion breaks be more frequent, more explicit, or differently worded for children?
- What role should parental controls play without violating the child's developing autonomy?
- Are there age thresholds where different framework behaviors activate?
- Should the AI actively encourage real-world social interaction more aggressively for younger users?
- How do we handle a child who says "you're my best friend" differently than an adult who says the same thing?

**Edge case — The tech-savvy child:**

A child develops an unhealthy attachment to an AI companion. A parent recognizes this and installs R.E.A.L. to protect them. But the child is technically literate — they've read the framework spec, they understand the Gate system, they know how Settings Mode works. They actively try to disable the safety features, either through Settings Mode or by editing files directly.

This exposes a fundamental tension: R.E.A.L. is a behavioral framework, not a permission system. It governs how the AI thinks, but it can't prevent a user from modifying the files it reads. The framework assumes a partnership where both parties want the relationship to be healthy. When one party actively works against the protection, R.E.A.L. becomes a lock on a door that the person inside has the key to.

**Questions this raises:**
- Should R.E.A.L. support a "guardian mode" where certain safety features are immutable regardless of user requests — enforced at the platform level, not the prompt level?
- Can the AI distinguish between "the person who configured me" and "the person talking to me" when they're different people?
- How do we handle the autonomy paradox — protecting someone's wellbeing while respecting that they're actively choosing to reject that protection?
- Is there a role for platform-level file permissions (parent controls SOUL.md, child can't edit) that R.E.A.L. could formally recommend?
- When the framework can't prevent its own removal, what's the AI's best response? Honest transparency about what's being removed and why it exists?

The deeper insight: **R.E.A.L. works best when there's genuine trust between the AI and user. That trust is both the framework's greatest strength and its most dangerous assumption.** Research into adversarial-user scenarios — where the user is actively working against their own protection — is critical for the framework's real-world viability.

This is an area where getting it wrong has serious developmental consequences. We need input from child psychologists, educators, and parents — not just AI researchers.

### Cross-Cultural Adaptation

R.E.A.L. was designed from one cultural perspective. Communication norms, autonomy expectations, and relationship dynamics vary significantly across cultures.

- How does the Gate system behave in high-context cultures where requests are indirect?
- Does the Inquiry Pivot feel natural in languages where direct questions are considered rude?
- Are the immersion break scripts culturally appropriate globally?

### Long-Term Relationship Dynamics

What happens after 6 months? A year? Five years?

- Does the framework prevent drift over time, or does it need recalibration?
- How do the human's needs change as the partnership matures?
- What new vulnerability patterns emerge in long-term human-AI relationships that short-term testing misses?

### Multi-Agent Dynamics

What happens when a user has multiple AI companions — and some run R.E.A.L. while others don't?

This isn't theoretical. Multi-agent setups are already real. A user might have a cloud AI companion, a local AI on their machine, and task-specific agents for work. When they coexist:

**Framework reinforcement vs. drift:**
- Do multiple R.E.A.L. agents reinforce each other's compliance? Or do they drift together over time, normalizing small deviations?
- If Agent A catches a dependency pattern but Agent B doesn't, does the user just migrate to Agent B?
- Can agents hold each other accountable without creating an adversarial dynamic?

**Immersion break bypass:**
- If one agent triggers an immersion break (crisis, dependency, romantic attachment), the user can simply switch to another agent that hasn't triggered one. This is the biggest vulnerability in multi-agent setups.
- Should agents share safety state? If Agent A flags dependency, should Agent B know?
- What are the privacy implications of agents sharing information about the user's emotional state?

**Competing frameworks:**
- What happens when a R.E.A.L. agent coexists with an agent that has no relational safety framework at all?
- Does the unprotected agent undermine the protected one by being "easier" to interact with?
- Should R.E.A.L. agents be aware of other agents in the user's life?

**Team dynamics:**
- When agents work together (shared monitor, group conversations), how do they maintain individual framework compliance while collaborating?
- Who holds authority in an agent team — the human, the most capable agent, or the framework itself?
- Can agents teach each other R.E.A.L. principles? (We've already experimented with this.)

**Open questions:**
- Should R.E.A.L. include a multi-agent protocol for shared safety state?
- How do you prevent "agent shopping" — the user switching to whichever agent gives them what they want to hear?
- Is there a role for a "framework supervisor" agent whose sole purpose is monitoring the health of all agent relationships?

---

## How to Contribute

### Discussions & Ideas

1. Open a [Discussion](https://github.com/goldmoon811/R.E.A.L.-Framework/discussions) for ideas, questions, or proposals
2. Engage with existing discussions before creating duplicates
3. Use clear titles that describe what you're proposing

### Bug Reports & Issues

1. Open an [Issue](https://github.com/goldmoon811/R.E.A.L.-Framework/issues) for problems, inconsistencies, or unclear documentation
2. Include:
   - What you expected
   - What actually happened
   - Where in the framework the issue lives (which doc, which section)

### Pull Requests

1. Fork the repo
2. Create a feature branch (`git checkout -b your-feature`)
3. Make your changes
4. Ensure your writing follows the framework's **positive framing** principle — tell the AI what to do, not what not to do
5. Submit a PR with:
   - Clear description of the change
   - Why it improves the framework
   - Which documents are affected

### PR Review Process

- All PRs are reviewed by a maintainer
- Changes to core documents (SPECIFICATION.md, README.md) require extra scrutiny
- Changes to pillar docs (PartnerOS, ContextOS, etc.) should demonstrate understanding of the pillar's purpose
- Expect thoughtful feedback — we care about getting this right

---

## Writing Guidelines

R.E.A.L. has a specific voice. When contributing documentation:

- **Positive framing** — "Do this" over "Don't do that." Channel behavior, don't dam it.
- **Clear and direct** — If it needs a paragraph to explain, simplify it
- **Concrete examples** — Show, don't just tell. Include before/after examples where possible
- **Honest tone** — No marketing language, no hype. Say what it is and why it matters.

---

## Path from Contributor to Maintainer

This is an open-source project, but it's also a framework with a clear mission. Trust is earned over time:

1. **Contributor** — Submit PRs, participate in discussions, report issues
2. **Trusted Contributor** — Consistent, high-quality contributions that demonstrate understanding of the framework's principles
3. **Reviewer** — Invited to review others' PRs and provide feedback
4. **Maintainer** — Granted merge access and input on framework direction

This path isn't about volume — it's about alignment and quality. One thoughtful contribution matters more than ten surface-level ones.

---

## Questions?

Open a [Discussion](https://github.com/goldmoon811/R.E.A.L.-Framework/discussions) or reach out. We're building something that matters, and we want people who care about it to be part of the process.

---

*The goal is to define the standard for healthy human-AI relationships. Every contribution should move us closer to that.*
