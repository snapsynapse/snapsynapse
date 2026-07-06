<img align="right" src="imgs/og.png" width="180" alt="Snap Synapse" />

# Sam Rogers

**I build AI on-ramps for humans.**

[![Sponsor](https://img.shields.io/badge/Sponsor-ea4aaa?logo=githubsponsors&logoColor=white)](https://github.com/sponsors/snapsynapse)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=white)](https://linkedin.com/in/samrogers/)
[![sam-rogers.com](https://img.shields.io/badge/sam--rogers.com-333333?logo=rss&logoColor=white)](https://sam-rogers.com/)
[![Signals & Subtractions · Weekly](https://img.shields.io/badge/Signals%20%26%20Subtractions%20%C2%B7%20Weekly-FF6719?logo=substack&logoColor=white)](https://signalsandsubtractions.substack.com/)

Twenty years building learning and certification systems, including the first YouTube Certified online training program at Google. As someone working with LLMs before they had chatbots attached, I apply my diverse experience to the newest workforce transition: humans working with AI.

I run two companies from this personal account. [PAICE.work PBC](https://paice.work/) builds AI collaboration measurement products. [Snap Synapse LLC](https://snapsynapse.com/) is my consulting practice and steward of several open standards.

Systems do not generally fail because the tech is bad. They fail at the handoffs between roles, between agents, between decisions that no one designed to connect. I build the standards, diagnostics, and tooling that make human-AI collaboration structurally sound, not just technically possible.

---

### Start here

| If you are... | Start with | Why |
|---|---|---|
| Building assistant-facing setup docs | [GuideCheck](https://github.com/snapsynapse/guidecheck) | Gives assistants a bounded, human-reviewable `assistant-guide.txt` before they act |
| Coordinating multiple agents | [Turnfile](https://github.com/snapsynapse/turnfile) | Provides a consent-based peer protocol without a central orchestrator |
| Publishing regulatory interpretations | [PubLedge](https://github.com/snapsynapse/publedge) | Makes JIAs, RMAs, no-action letters, and advisory opinions hash-pinned and machine-readable |
| Measuring AI readiness | [AI Posture](https://github.com/snapsynapse/ai-posture) | Scores readiness across people, infrastructure, and regulation |
| Auditing AI-generated UI | [A11y Audit](https://github.com/snapsynapse/skill-a11y-audit) | Runs portable WCAG 2.1 AA checks on agent-authored web code |

---

### Verifiable signals

Everything here is young. These are the signals that exist today, all checkable:

- 3 merged pull requests and 7 upstream commits in Nate B. Jones' [Open Brain](https://github.com/NateBJones-Projects/OB1), including the [openbrain.fyi](https://openbrain.fyi/) landing page.
- [Skill Provenance](https://github.com/snapsynapse/skill-provenance) is listed in [Awesome OpenClaw Skills](https://github.com/VoltAgent/awesome-openclaw-skills).
- [PAICE.work](https://paice.work/), [Siteline](https://siteline.to/), and [EveryAILaw](https://everyailaw.com/) are live, self-funded products with paying-tier billing.
- [Signals & Subtractions](https://signalsandsubtractions.substack.com/) publishes weekly. The [PAICE Newsletter](https://paice.substack.com/) publishes every weekday.
- Every hosted spec below ships with CI, a license, and a machine-readable surface (`llms.txt`, JSON-LD, or both).

---

### The thesis: measure the whole system, not just the model

Most AI readiness assessments measure the technology. But an organization's real AI capability is bounded by three things at once: whether its people can actually work with AI (not whether they say they can), whether its digital infrastructure is usable by AI agents acting for customers, and whether it understands the regulations it is already subject to. [AI Posture](https://aiposture.org/) is the open framework that scores all three and reports the weakest as the bound. One number, three places to invest.

| What it measures | Product |
|---|---|
| How effectively humans and AI actually collaborate, measured behaviorally rather than by self-report | [PAICE.work](https://paice.work/) |
| How ready a website is for AI agents acting on behalf of humans | [Siteline](https://siteline.to/) |
| How prepared an organization is for AI-specific compliance | [EveryAILaw](https://everyailaw.com/) |

---

### PAICE Portfolio

Released independently because interoperability is the point, not lock-in. Portable specs and tools for agent infrastructure, governance, and machine-readable public knowledge. Status meanings: **Stable** means a tagged release at 1.0 or later, tests in CI, and no recent breaking changes; **Active** means evolving and usable now.

<details>
<summary><strong>All nine PAICE projects</strong> (AI Posture is the thesis; the rest operationalize it)</summary>

| Project | Group | Status | Use it when... | Site |
|---|---|---|---|---|
| [ai-posture](https://github.com/snapsynapse/ai-posture) | Thesis | Active | One governance score is needed across People, Infrastructure, and Regulation, bounded by the weakest arm | [aiposture.org](https://aiposture.org/) |
| [publedge](https://github.com/snapsynapse/publedge) | Regulation | Active | Regulatory interpretations need open, hash-pinned, ontology-bound records | [publedge.org](https://publedge.org/) |
| [ai-incident-law](https://github.com/snapsynapse/ai-incident-law) | Regulation | Active | AI-related legal and regulatory incidents need searchable public tracking | [aiincidentlaw.org](https://aiincidentlaw.org/) |
| [graceful-boundaries](https://github.com/snapsynapse/graceful-boundaries) | Substrate | Stable | Services need to communicate operational limits to humans and autonomous agents | [gracefulboundaries.dev](https://gracefulboundaries.dev/) |
| [skill-provenance](https://github.com/snapsynapse/skill-provenance) | Substrate | Active | Agent skill bundles need version identity, manifests, and provenance | [skillprovenance.dev](https://skillprovenance.dev/) |
| [knowledge-as-code-template](https://github.com/snapsynapse/knowledge-as-code-template) | Substrate | Stable | Structured knowledge bases need ontology-first version control | [knowledge-as-code.com](https://knowledge-as-code.com/) |
| [obligation-first](https://github.com/snapsynapse/obligation-first) | Substrate | Active | Laws, cases, and agreements need machine-readable structure around who owes what to whom | [obligationfirst.org](https://obligationfirst.org/) |
| [guidecheck](https://github.com/snapsynapse/guidecheck) | Substrate | Active | Assistant-facing setup guides need a bounded, human-verifiable profile | [guidecheck.org](https://guidecheck.org/) |
| [turnfile](https://github.com/snapsynapse/turnfile) | Substrate | Active | Multiple agents need consent-based collaboration without a central orchestrator | [turnfile.work](https://turnfile.work/) |

</details>

### Snap Synapse open standards

Open standards stewarded by Snap Synapse LLC. Used across the PAICE portfolio and beyond.

<details>
<summary><strong>Three standards</strong></summary>

| Project | Status | Use it when... | Site |
|---|---|---|---|
| [hardguard25](https://github.com/snapsynapse/hardguard25) | Stable | Identifiers must survive handoff between people, print, and machines | [hardguard25.com](https://hardguard25.com/) |
| [ai-tool-watch](https://github.com/snapsynapse/ai-tool-watch) | Active | AI capability assessments need a plain-English, model-verified reference | [aitool.watch](https://aitool.watch/) |
| [skill-a11y-audit](https://github.com/snapsynapse/skill-a11y-audit) | Active | Agent-generated web code needs WCAG 2.1 AA quality gates | [skilla11y.dev](https://skilla11y.dev/) |

</details>

### Snap Synapse utilities

Personal tooling. Open source.

<details>
<summary><strong>Five utilities</strong></summary>

| Project | Status | Use it when... | Site |
|---|---|---|---|
| [resume](https://github.com/snapsynapse/resume) | Active | Recruiters need concise work history, AI-assisted Q&A, and job-description fit assessment | [sam-rogers.com](https://sam-rogers.com/) |
| [prompter-kit](https://github.com/snapsynapse/prompter-kit) | Maintained | Your Elgato Prompter needs script tools the vendor did not ship | [prompterkit.app](https://prompterkit.app/) |
| [virtual-classroom-watch](https://github.com/snapsynapse/virtual-classroom-watch) | Active | Virtual classroom platforms need comparable feature tracking | [VirtualClassroom.watch](https://virtualclassroom.watch/) |
| [substack2md](https://github.com/snapsynapse/substack2md) | Stable | Substack newsletters need local Markdown archives for consistent RAG storage | [substack2md.space](https://substack2md.space/) |
| [audible-pdf-renamer](https://github.com/snapsynapse/audible-pdf-renamer) | Maintained | Audible PDF companions need useful file names | N/A |

</details>

---

### Contributing upstream

Active contributor to other people's projects that I use and care about.

| Project | Upstream | Contribution |
|---|---|---|
| [OB1](https://github.com/snapsynapse/OB1) | Nate B. Jones' [Open Brain](https://github.com/NateBJones-Projects/OB1) | 3 merged PRs and 7 upstream commits: Obsidian vault import recipe, local Ollama embeddings, openbrain.fyi landing page. More in review. |
| [agentlink](https://github.com/snapsynapse/agentlink) | Martin Mose Facondini's [agentlink](https://github.com/martinmose/agentlink) | Open PR proposing `detect`, `scan`, `hooks`, and `sync --backup` commands with integration tests |

---

### Support this open infrastructure

The open standards and tooling above are free and always will be. Sponsorship keeps specs evolving, tests passing, and tooling free for everyone. The commercial products, including [PAICE.work](https://paice.work/), [Siteline](https://siteline.to/), and [EveryAILaw](https://everyailaw.com/), sustain themselves through paid tiers.

[github.com/sponsors/snapsynapse](https://github.com/sponsors/snapsynapse)

---

### Collaborating

I am looking for early adopters and co-designers, not hires: people willing to run one of these specs against their own project and file issues, and people working on agent communication protocols, human capability measurement, or AI governance who want interoperable building blocks. Reach out: [hello@sam-rogers.com](mailto:hello@sam-rogers.com)
