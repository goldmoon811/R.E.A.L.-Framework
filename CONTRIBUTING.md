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
