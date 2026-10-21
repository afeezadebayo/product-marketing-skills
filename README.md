# Product Marketing — SKILL.md files for AI agents

[![13 skills](https://img.shields.io/badge/skills-13-0b7285)](#whats-inside)
[![Format: Agent Skills](https://img.shields.io/badge/format-SKILL.md-5f3dc4)](https://agentskills.io/specification)
[![Works with Claude Code & Codex](https://img.shields.io/badge/works%20with-Claude%20Code%20%7C%20Codex%20%7C%20Claude.ai-1c7ed6)](#install)
[![Licence: CC BY 4.0](https://img.shields.io/badge/licence-CC%20BY%204.0-2b8a3e)](https://creativecommons.org/licenses/by/4.0/)

Free, ready-to-run **product marketing** skills for **Claude, Claude Code, OpenAI Codex** and any agent that reads
the [Agent Skills](https://agentskills.io/specification) format. Positioning, messaging, ICP, customer research,
win-loss, competitive intelligence, pricing, go-to-market plans, launches, sales enablement, partner marketing and
customer proof. Each skill is a single `SKILL.md`: a senior practitioner's workflow — when to use it, the inputs to
ask for, a numbered process, decision rules, an output template and sources — loaded only when a task needs it.

Part of the [Marketing Skills library](https://github.com/afeezadebayo/marketing-skills) by
[Afeez Adebayo](https://afeezadebayo.com) · [Browse online](https://afeezadebayo.com/skills-md/marketing/product-marketing/)

## Install

Each skill is its own folder with a `SKILL.md`, so you can drop any folder straight into an agent.

**Claude Code**
```bash
git clone https://github.com/afeezadebayo/product-marketing-skills.git
cp -r product-marketing-skills/product-marketing-audit ~/.claude/skills/        # all projects
# or  .claude/skills/   inside one project
```

**OpenAI Codex**
```bash
cp -r product-marketing-skills/product-marketing-audit ~/.agents/skills/         # all repos
```

**Claude.ai / Desktop** — zip a skill folder, then **Settings → Capabilities → Skills → Upload skill**
(code execution must be enabled). To bulk-load the whole category into a Claude Project, custom GPT or
knowledge base, grab the single-folder `.zip` from the
[library page](https://afeezadebayo.com/skills-md/marketing/product-marketing/).

Then start a new session and ask your agent which skills it can use.

## What's inside

| Skill | What it does |
|---|---|
| [`product-marketing-audit`](product-marketing-audit/SKILL.md) | Audit the product marketing function end to end across ten areas, scored with a 90-day plan. The entry point. |
| [`positioning`](positioning/SKILL.md) | Build or repair product positioning from best-fit customers, real alternatives and proof. |
| [`messaging-framework`](messaging-framework/SKILL.md) | Build messaging frameworks from positioning and customer language, tested across channels. |
| [`ideal-customer-profile`](ideal-customer-profile/SKILL.md) | Build ICPs and personas from evidence: retention, expansion, triggers and disqualifiers. |
| [`customer-research-interviews`](customer-research-interviews/SKILL.md) | Plan and run JTBD switch interviews, lost-prospect and churn interviews for product marketing. |
| [`win-loss-analysis`](win-loss-analysis/SKILL.md) | Set up a win-loss programme with neutral buyer interviews and a consistent reason taxonomy. |
| [`competitive-intelligence`](competitive-intelligence/SKILL.md) | Build a competitive intelligence programme: tiered competitors, battlecards, comparison pages. |
| [`pricing-packaging`](pricing-packaging/SKILL.md) | Review and redesign pricing and packaging: value metrics, tiers, willingness-to-pay research. |
| [`go-to-market-plan`](go-to-market-plan/SKILL.md) | Build GTM plans for new products, segments and markets: beachhead, motion, channels, metrics. |
| [`product-launch`](product-launch/SKILL.md) | Plan product and feature launches that drive adoption: tiering, readiness, runbooks, retros. |
| [`sales-enablement`](sales-enablement/SKILL.md) | Build sales enablement that wins deals: narrative, stage-based content, onboarding, measurement. |
| [`case-studies-customer-proof`](case-studies-customer-proof/SKILL.md) | Build a customer proof programme: case studies, testimonials, reviews and references. |
| [`partner-marketing`](partner-marketing/SKILL.md) | Plan partner marketing that drives pipeline: tiers, joint value propositions, co-selling. |

## How these skills work

Agents use *progressive disclosure*: they read each skill's `name` and `description` (~100 tokens) at the start
of a session and load the full `SKILL.md` only when your request matches — so you can install many without
filling the context window.

## Author & licence

By [**Afeez Adebayo**](https://afeezadebayo.com) — Marketing, SEO & Growth (SEO & Organic Growth at Grey, YC W22).
[LinkedIn](https://www.linkedin.com/in/afeez-adebayo/) · [X](https://x.com/za_icon) · [Newsletter](https://afeezadebayo.com/newsletter/)

Released under [**CC BY 4.0**](https://creativecommons.org/licenses/by/4.0/) — use, share and adapt, including
commercially, with credit to Afeez Adebayo and a link to the source page in each file.

<sub>Keywords: product marketing skills, SKILL.md, Agent Skills, Claude skills, Claude Code skills, Codex skills,
AI agent skills, positioning, messaging framework, ideal customer profile, win-loss analysis, competitive
intelligence, pricing and packaging, go-to-market plan, product launch, sales enablement, case studies, partner
marketing.</sub>
