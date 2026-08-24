# Startup Skill

[![Version](https://img.shields.io/github/v/release/dharshith8/startup-skill?label=version)](https://github.com/dharshith8/startup-skill/releases)
[![License: MIT](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![GitHub stars](https://img.shields.io/github/stars/dharshith8/startup-skill)](https://github.com/dharshith8/startup-skill/stargazers)

<p align="center">
  <img src="assets/banner.png" alt="Startup Skill — From startup idea to validated strategy. In one afternoon. Radically honest. Completely free." width="100%" />
</p>

What a $10K strategy consultant would deliver: market research, competitive battle cards, positioning, financial projections, and a 30-day action plan. If your idea should die, it will tell you. Plus 50 more skills covering the rest of the founder stack — fundraising, sales, product, recruiting, engineering, legal, operations, customer success, and marketing.

Works with [Claude Code](https://claude.ai/claude-code) and any agent that supports skills.

**Website:** [startupskill.me](https://startupskill.me)

**Latest release:** [v1.10.0](https://github.com/dharshith8/startup-skill/releases/tag/v1.10.0)

**Contributions welcome!** [Open a PR](#contributing) or [an issue](https://github.com/dharshith8/startup-skill/issues).

## Flagship Skills

Deep, multi-phase research workflows for taking an idea from scratch to a validated plan.

| Skill | What you get |
|-------|-------------|
| [startup-design](startup-design/) | Complete startup strategy: market research, customer discovery, competitive analysis, brand, product definition, financial projections, and validation experiments. 8 phases plus pre-flight check and customer interview gate, 30+ structured deliverables. |
| [startup-competitors](startup-competitors/) | Battle cards for every competitor, pricing landscape, feature matrix, and strategic report. Built from real reviews, forums, web data, and reviewed social/community source packets when provided. |
| [startup-positioning](startup-positioning/) | Market positioning using April Dunford's framework. Positioning doc, competitive alternatives map, market category analysis, and messaging implications. |
| [startup-pitch](startup-pitch/) | Investor-ready pitch in multiple formats: 10-min, 5-min, 2-min, 1-min elevator, email, and a slide-by-slide deck outline. Includes scoring rubric, Q&A prep, and investor roleplay practice. |

## Founder Stack Skills

50 single-purpose skills for the day-to-day work of running a startup — fundraising, sales, product, recruiting, engineering, legal, operations, customer success, and marketing. Every skill reads a shared `.agents/startup-context.md` (company stage, product, market, team, metrics) via [startup-context](startup-context/), so output is tailored to your specific startup instead of generic.

Adapted from the best open-source Claude Skills we could find for each founder task — see [Acknowledgments](#acknowledgments) for full attribution.

<details>
<summary><strong>Foundation</strong></summary>

| Skill | What you get |
|-------|-------------|
| [startup-context](startup-context/) | Interviews you once and writes `.agents/startup-context.md` — the shared context every other Founder Stack skill reads first. |

</details>

<details>
<summary><strong>Fundraising</strong></summary>

| Skill | What you get |
|-------|-------------|
| [pitch-deck](pitch-deck/) | Slide-by-slide pitch deck content and narrative for seed/Series A. |
| [investor-research](investor-research/) | Identify, qualify, and prioritize investors by stage, sector, check size, and portfolio fit. |
| [data-room](data-room/) | Due diligence checklists, document organization, and drafts for missing items. |
| [fundraising-email](fundraising-email/) | Investor cold intros, warm follow-ups, update emails, and thank-you notes. |
| [accelerator-application](accelerator-application/) | Apply to YC, Techstars, and 40+ other accelerators — directory, application drafts, interview prep. |

</details>

<details>
<summary><strong>Sales & BD</strong></summary>

| Skill | What you get |
|-------|-------------|
| [cold-outreach](cold-outreach/) | Cold emails, LinkedIn messages, and follow-up sequences for B2B prospecting. |
| [sales-script](sales-script/) | Demo scripts, discovery call frameworks, objection handling, closing playbooks. |
| [proposal-generation](proposal-generation/) | Sales proposals, SOWs, and pricing quotes. |
| [lead-scoring](lead-scoring/) | ICP criteria, lead qualification frameworks, and scoring models. |
| [partnership-outreach](partnership-outreach/) | Partnership proposals, integration pitches, co-marketing outreach. |

</details>

<details>
<summary><strong>Product & Strategy</strong></summary>

| Skill | What you get |
|-------|-------------|
| [prd-writing](prd-writing/) | Product requirements documents, feature specs, user story sets. |
| [user-research-synthesis](user-research-synthesis/) | Synthesize interviews, surveys, and support tickets into insights and personas. |
| [roadmap-planning](roadmap-planning/) | Product roadmap with timeline views, dependencies, milestones. |
| [mvp-scoping](mvp-scoping/) | MVP scope — what to build, cut, and defer. |
| [competitive-analysis](competitive-analysis/) | Quick competitor research — feature comparison, positioning, pricing benchmarks. |
| [market-research](market-research/) | TAM/SAM/SOM sizing, trend identification, market hypothesis validation. |
| [review-mining](review-mining/) | Mine Trustpilot, G2, Capterra, and app store reviews for pain points and voice-of-customer language. |
| [daily-product-digest](daily-product-digest/) | Summarize trending launches on Product Hunt, Hacker News, Indie Hackers. |
| [competitor-monitoring](competitor-monitoring/) | Ongoing tracking of competitor pricing, features, hiring, and positioning changes. |

</details>

<details>
<summary><strong>Recruiting & Team</strong></summary>

| Skill | What you get |
|-------|-------------|
| [job-description](job-description/) | Compelling job descriptions without corporate jargon. |
| [interview-kit](interview-kit/) | Interview questions, scorecards, take-homes, rubrics, comp benchmarking. |
| [sourcing-outreach](sourcing-outreach/) | Recruiting outreach — LinkedIn InMails, cold emails, referral requests. |
| [employer-brand](employer-brand/) | Careers page copy, team culture docs, engineering blog posts. |

</details>

<details>
<summary><strong>Engineering</strong></summary>

| Skill | What you get |
|-------|-------------|
| [architecture-design](architecture-design/) | System architecture — service boundaries, data models, API design, infra planning. |
| [code-review](code-review/) | Thorough code review — correctness, security, performance, maintainability. |
| [cicd-setup](cicd-setup/) | CI/CD pipelines — GitHub Actions, testing, deployment, release automation. |
| [tech-stack-eval](tech-stack-eval/) | Evaluate and select frameworks, databases, hosting, and third-party services. |
| [security-review](security-review/) | Security audit — OWASP top 10, auth flows, data handling, dependency vulnerabilities. |

</details>

<details>
<summary><strong>Legal & Compliance</strong></summary>

| Skill | What you get |
|-------|-------------|
| [privacy-policy](privacy-policy/) | Privacy policy, cookie policy, data processing documentation. Not a substitute for legal counsel. |
| [terms-of-service](terms-of-service/) | Terms of service, acceptable use policies, SaaS agreements. Not a substitute for legal counsel. |
| [contract-review](contract-review/) | Flag risks in vendor, partnership, or customer contracts. |
| [soc2-prep](soc2-prep/) | SOC 2 readiness — policy templates, control mapping, evidence checklists. |

</details>

<details>
<summary><strong>Operations</strong></summary>

| Skill | What you get |
|-------|-------------|
| [process-docs](process-docs/) | SOPs, internal playbooks, and runbooks. |
| [board-update](board-update/) | Investor updates, board decks, monthly/quarterly reports. |

</details>

<details>
<summary><strong>Customer Success</strong></summary>

| Skill | What you get |
|-------|-------------|
| [onboarding-flow](onboarding-flow/) | Activation flows, welcome sequences, time-to-value optimization. |
| [support-docs](support-docs/) | Help center articles, FAQs, troubleshooting guides, API docs. |
| [feedback-synthesis](feedback-synthesis/) | Categorize and prioritize customer feedback themes. |
| [churn-analysis](churn-analysis/) | Churn drivers, retention experiments, win-back campaigns. |
| [sentiment-monitoring](sentiment-monitoring/) | Monitor your product's reviews and mentions across platforms, with response drafts. |

</details>

<details>
<summary><strong>Marketing & Growth</strong></summary>

| Skill | What you get |
|-------|-------------|
| [landing-page](landing-page/) | Landing page copy, layout, CTAs, conversion optimization. |
| [content-strategy](content-strategy/) | Blog strategy, SEO content calendars, thought leadership. |
| [seo-technical](seo-technical/) | Technical SEO audit — site structure, meta tags, schema markup, Core Web Vitals. |
| [email-marketing](email-marketing/) | Newsletters, drip sequences, lifecycle emails, re-engagement flows. |
| [social-content](social-content/) | LinkedIn posts, X/Twitter threads, content repurposing. |
| [launch-strategy](launch-strategy/) | Product launch plan — Product Hunt, Hacker News, press, community seeding. |
| [founder-thought-leadership](founder-thought-leadership/) | Founder IP and personal brand on X and LinkedIn. |
| [community-discovery](community-discovery/) | Find Slack, Discord, Reddit, and forum communities where customers hang out. |
| [event-hosting](event-hosting/) | Plan and promote tech events and meetups on Luma. |
| [earned-media-outreach](earned-media-outreach/) | Find podcasts, journalists, and newsletter writers for earned media exposure. |

</details>

## Usage

Describe what you need — skills trigger automatically:

> *"I want to build a SaaS for real estate agents that automates follow-up emails. Is it worth building?"*

**→ `startup-design`** runs the full process: pre-flight check, 8 phases, customer discovery gate

---

> *"Who are my competitors in the project management space for creative agencies? I need battle cards and a pricing comparison."*

**→ `startup-competitors`** profiles 5-8+ competitors across 3 research waves

---

> *"Quick validation — fast track mode."*

**→ `startup-design`** runs a compressed go/no-go analysis

---

> *"How should we position our product? We're in the project management space but we're different from Asana and Monday."*

**→ `startup-positioning`** builds positioning through Dunford's 5+1 components

---

> *"Prepare my pitch — I'm raising 500K pre-seed. We have 45 active customers growing 20% MoM."*

**→ `startup-pitch`** builds pitch narratives in multiple formats with scoring and Q&A prep

Or invoke directly: `/startup:startup-design`, `/startup:startup-competitors`, `/startup:startup-positioning`, `/startup:startup-pitch`

Founder Stack skills work the same way — describe the task and the right skill triggers, or invoke directly, e.g. `/startup:pitch-deck`, `/startup:cold-outreach`, `/startup:code-review`. First run `/startup:startup-context` (or just say "let me tell you about my startup") so downstream skills have context to work from.

> **Token usage:** These skills run multiple research agents and can consume a large number of tokens. For the best experience, use [Claude Max 5x](https://claude.ai/upgrade). If a session hits the limit, just ask Claude to "resume from where you left off" — it will pick up the process.

## Installation

### Claude Code Plugin (Recommended)

```bash
claude plugin marketplace add dharshith8/startup-skill
claude plugin install startup@startup-skill
```

<details>
<summary><strong>Claude.ai (Web App)</strong></summary>

Download `.skill` files from the [Releases page](https://github.com/dharshith8/startup-skill/releases), then upload in **Settings → Skills**.

</details>

<details>
<summary><strong>Other Methods</strong></summary>

```bash
# CLI Install
npx skills add dharshith8/startup-skill

# Clone and copy (all 54 skills)
git clone https://github.com/dharshith8/startup-skill.git
for skill in startup-skill/*/; do
  [ -f "$skill/SKILL.md" ] && cp -r "$skill" .agents/skills/
done

# Or copy just the skills you want, e.g.:
cp -r startup-skill/startup-design .agents/skills/
cp -r startup-skill/pitch-deck .agents/skills/

# Git submodule
git submodule add https://github.com/dharshith8/startup-skill.git .agents/startup-skill

# SkillKit (works with Claude Code, Cursor, Copilot, etc.)
npx skillkit install dharshith8/startup-skill
```

</details>

<details>
<summary><strong>Updating</strong></summary>

**Claude Code Plugin:**
```bash
claude plugin update startup@startup-skill
```

> If the update doesn't pick up new changes, refresh the marketplace source and reinstall:
> ```bash
> claude plugin uninstall startup@startup-skill
> claude plugin marketplace remove startup-skill
> claude plugin marketplace add dharshith8/startup-skill
> claude plugin install startup@startup-skill
> ```

**Claude.ai:** Download the latest `.skill` files from the [Releases page](https://github.com/dharshith8/startup-skill/releases) and re-upload in **Settings → Skills**.

**CLI / SkillKit:** Re-run the install command — it overwrites the previous version:
```bash
npx skills add dharshith8/startup-skill
# or
npx skillkit install dharshith8/startup-skill
```

**Git Submodule:**
```bash
git submodule update --remote .agents/startup-skill
```

</details>

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for details.

## Acknowledgments

The 50 Founder Stack skills are adapted from [Startup Founder Skills](https://github.com/shawnpang/startup-founder-skills) by Shawn Pang (MIT), which itself built on multiple open-source Claude Skills projects. Each original SKILL.md was read, its core frameworks and workflows extracted, and adapted into a consistent format — in some cases merging multiple source skills into one.

This project builds on the work of:

- [Shawn Pang](https://github.com/shawnpang/startup-founder-skills) — Startup Founder Skills, the direct source for the Founder Stack skills in this repo
- [Corey Haines](https://github.com/coreyhaines31/marketingskills) — Marketing Skills for AI Agents (landing page, content strategy, email marketing, social content)
- [Alireza Rezvani](https://github.com/alirezarezvani/claude-skills) — Engineering, architecture, CI/CD, sales, and compliance skills
- [Pawel Huryn](https://github.com/phuryn/pm-skills) — Product management skills (PRDs, roadmaps, research, privacy)
- [Jeff Allan](https://github.com/Jeffallan/claude-skills) — Code review and security review skills
- [Brian Wagner](https://github.com/BrianRWagner/ai-marketing-claude-code-skills) — Cold outreach and social content skills
- [Athina AI](https://github.com/athina-ai/goose-skills) — Lead scoring and churn analysis skills
- [Daniel Agrici](https://github.com/AgriciDaniel/claude-seo) — Technical SEO skills
- [Daniel Mendes](https://github.com/dmend3z/tribo-skills) — Launch strategy and marketing skills
- [Manoj Bajaj](https://github.com/manojbajaj95/claude-gtm-plugin) — Onboarding and GTM skills

## License

[MIT](LICENSE) — the Founder Stack skills retain their upstream MIT attribution per the Acknowledgments section above.
