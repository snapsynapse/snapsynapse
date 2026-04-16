# Sam Rogers

I build AI on-ramps for humans.

Founder, [PAICE.work](https://paice.work/) · [Snap Synapse](https://snapsynapse.com/)

Systems don't generally fail because the tech is bad. They fail at the handoffs between roles, between agents, between decisions that no one designed to connect. I build the standards, diagnostics, and tooling that make human-AI collaboration structurally sound, not just technically possible.

Interoperability over integration · Measurement over intuition · Structure over speed

### Aggregated Intelligence

True intelligence in the AI era is composite — human and machine capabilities combined into something neither can achieve alone. PAICE.work operationalizes this through an Aggregated Intelligence Posture (AIP) measured across three vectors:

- **People** — [PAICE.work](https://paice.work/) measures how effectively humans and AI actually collaborate, behaviorally, not by self-report
- **Infrastructure** — [Siteline](https://siteline.to/) measures how ready an organization's digital presence is for AI agents acting on behalf of humans
- **Regulation** — [EveryAILaw](https://everyailaw.com/) measures how informed and prepared an organization is for AI-specific compliance

An organization's AIP is bounded by its weakest vector. One score, one slide, three places to invest.

---

### Start here

The six pinned repos, in display order, with the pitch:

1. [graceful-boundaries](https://github.com/snapsynapse/graceful-boundaries) — Specification for how services communicate operational limits and error context to humans and autonomous agents. Start here if you're designing an API that agents will hit.
2. [skill-provenance](https://github.com/snapsynapse/skill-provenance) — Version identity and integrity verification for Agent Skills. SHA-256 manifests that travel with the bundle. Start here if you ship skills across surfaces.
3. [turnfile](https://github.com/snapsynapse/turnfile) — File-based protocol for LLM agents collaborating on a shared codebase without real-time channels. Start here if two agents keep stepping on each other.
4. [knowledge-as-code-template](https://github.com/snapsynapse/knowledge-as-code-template) — Template for building structured, agent-accessible knowledge bases. Database-less static sites, JSON APIs, and multi-output from markdown. Powers [EveryAILaw](https://everyailaw.com/) and [AITool.watch](https://aitool.watch/).
5. [AITool.watch](https://github.com/snapsynapse/ai-tool-watch) — Evidence-backed reference for AI capabilities, pricing, and platform support across major providers. Start here if you're picking models and tired of vendor marketing.
6. [substack2md](https://github.com/snapsynapse/substack2md) — Local markdown archive of your favorite Substack newsletters. The oldest and most-used thing here.

---

### PAICE Portfolio

Measurement and governance infrastructure for Aggregated Intelligence. Nine projects owned by PAICE.work PBC, hosted in this org.

Revenue Products

- [PAICE.work](https://paice.work/) — People vector. Behavioral diagnostics for People + AI Collaboration Effectiveness.
- [Siteline](https://siteline.to/) — Infrastructure vector. Grades whether a website presents a usable path for AI agents.
- [EveryAILaw](https://everyailaw.com/) — Regulation vector. Obligation-first AI regulation reference for compliance teams and AI agents.

Open Infrastructure

Released independently because interoperability is the point, not lock-in. Each was built because the existing ecosystem couldn't deliver fast enough.

- [graceful-boundaries](https://github.com/snapsynapse/graceful-boundaries) — How services communicate operational limits and error context to humans and autonomous agents
- [turnfile](https://github.com/snapsynapse/turnfile) — File-based coordination for LLM agents collaborating on shared codebases
- [skill-provenance](https://github.com/snapsynapse/skill-provenance) — Version tracking for agent skill bundles across sessions, surfaces, and platforms
- [skill-a11y-audit](https://github.com/snapsynapse/skill-a11y-audit) — Drop-in WCAG 2.1 AA accessibility audit for AI coding agents
- [knowledge-as-code-template](https://github.com/snapsynapse/knowledge-as-code-template) — Pattern for human and machine-readable structured knowledge bases
- [AITool.watch](https://github.com/snapsynapse/ai-tool-watch) — What AI tools can actually do: capabilities, pricing, platform support

---

### Snap Synapse utilities

Personal tooling in the `snapsynapse` org. Not part of the PAICE Portfolio brand. Some have users. All are open source.

- [hardguard25](https://github.com/snapsynapse/hardguard25) — Human-friendly 25-character alphabet for unambiguous IDs
- [agentlink](https://github.com/snapsynapse/agentlink) — Sync one AGENTS.md to every AI coding tool via symlinks. Fork of [martinmose/agentlink](https://github.com/martinmose/agentlink); contributing enhancements back upstream ([PR #2](https://github.com/martinmose/agentlink/pull/2)).
- [substack2md](https://github.com/snapsynapse/substack2md) — Local markdown archive of Substack newsletters

---

### Contributing upstream

I ship into other people's projects too, because fixing something in someone else's repo is sometimes the right move.

- [martinmose/agentlink#2](https://github.com/martinmose/agentlink/pull/2) — CLI enhancements: `detect`, `scan`, `hooks`, `sync --backup`, global config, integration tests

More as they land.

---

### Companies

- [PAICE.work PBC](https://paice.work/) measures how effectively people and AI systems collaborate. Not whether teams use AI, but whether the collaboration is actually working. Behavioral diagnostics for People + AI Collaboration Effectiveness.
- [Snap Synapse LLC](https://snapsynapse.com/) helps teams and orgs apply AI responsibly, without the usual drama or damage. Structured implementations that move from AI promise to AI practice.

---

### Support this open infrastructure

Everything here is free and always will be. Sponsorship keeps specs evolving, tests passing, and tooling free for everyone.

[github.com/sponsors/snapsynapse](https://github.com/sponsors/snapsynapse)

---

### Collaborating

Currently looking for people working on agent communication protocols, human capability measures, AI regulations and governance structures, and aggregate intelligence infrastructure.

Good first issues to try:

- [graceful-boundaries/issues](https://github.com/snapsynapse/graceful-boundaries/issues)
- [turnfile/issues](https://github.com/snapsynapse/turnfile/issues)
- [skill-provenance/issues](https://github.com/snapsynapse/skill-provenance/issues)

Reach out: hello @ sam-rogers .com

---

### Elsewhere

- [Signals & Subtractions](https://signalsandsubtractions.substack.com/) — weekly newsletter
- [PAICE.work Substack](https://paice.substack.com/) — weekday updates
- [dev.to/snapsynapse](https://dev.to/snapsynapse) — new releases
- [LinkedIn](https://linkedin.com/in/samrogers/) — profile
- [sam-rogers.com](https://sam-rogers.com/) — personal blog
