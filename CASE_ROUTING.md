# Application Case Routing

This document is the canonical routing layer for application use of the portfolio cases. It is requirement-first: choose the case that proves the requirement most directly, then add at most one backup case when it adds a distinct signal.

## Positioning and claim guardrails

**AI Product & Systems Orchestration | Agentic AI · Automation · Evaluation · Governance**

The portfolio describes product thinking, requirements, orchestration, validation and governance in AI-assisted delivery. It does not claim classic Python development, classic software engineering, senior or architect level, or manual authorship of every AI-assisted code line.

Case status is evidence-bound. A repository, plan, screenshot, syntax check or green placeholder workflow is not silently upgraded to a production, runtime or user-adoption claim.

## Portfolio hierarchy

### Core anchors

1. **Sample Brain** — broadest product and systems case: local-first audio workflow, requirements, agent orchestration, evaluation and QA.
2. **Claire de Binare** — strongest governance and evidence case: deterministic states, fail-closed gates, auditability and authority boundaries.
3. **Traumtänzer** — strongest Responsible-AI case: safety, privacy, claims governance and concept-to-system boundaries.
4. **Agent Orchestration Case** — direct proof of bounded multi-agent routing, lane authority and evidence-based convergence.

### Targeted application modules

5. **Everlast-AI** — Product Discovery, Product Scoping, requirement extraction, voice UX and decision quality under a tight timebox.
6. **Clipboard-Brudi** — AI workflow tooling, human-agent handoff, operator UX, local-first automation and deliberate reduction of unnecessary AI.
7. **modusmono-blog** — Creative Tech, concept-to-digital-experience, information/content architecture and AI-assisted web delivery.

The targeted modules add precision; they do not replace a core anchor when an anchor carries the requirement more strongly.

## Case cards

### Everlast-AI

**Strongest signal:** extracting a usable product scope from a 72-hour challenge and making explicit trade-offs for a controllable voice interaction.

**Good role and requirement matches**

- AI Product Manager, Product Discovery, Product Operations, Voice UX or AI Enablement discovery roles.
- Requirements extraction, time-boxed MVP definition, prioritisation, interaction design, Definition of Done and evidence-aware decision making.

**Prefer it over Sample Brain, Claire or Traumtänzer when**

- the vacancy asks for short-cycle discovery, product scoping, voice or multimodal UX, or translating an ambiguous brief into a reviewable flow;
- the interviewer needs an example of deciding what to exclude under time pressure.

**Do not use it when**

- the requirement is production desktop engineering, STT/ML research, a shipped end-to-end voice product, or a completed challenge delivery;
- the role expects a claim about runtime reliability. The current evidence does not support that.

**1-sentence version**

> In a 72-hour voice-app challenge, I turned an open brief into a bounded Hotkey → recording → local transcription → optional enrichment flow, with explicit non-goals and evidence gates.

**3-sentence version**

> The challenge required a desktop Voice Intelligence app in a very short time. I focused on product scoping: extracted the core interaction, chose an offline-first Vosk direction, limited the result space to raw text plus three presets, and defined review criteria. The repository evidence supports the requirements and decisions, while the divergent `master`/`main` states do not justify a finished end-to-end claim.

**Interview version**

> I would explain the trade-off before the technology: the useful decision was to make one controllable voice loop legible under a 72-hour constraint. I separated challenge requirements, design choices and implementation evidence, and kept text-to-speech, avatars and always-on behaviour out of scope. I would also say plainly that `master` and `main` diverged and that the available smoke evidence does not prove recording, Vosk, enrichment, insertion or the demo video.

**Evidence**

- [Portfolio case study on the documented default branch](https://github.com/jannekbuengener/Everlast-AI/blob/master/docs/PORTFOLIO_CASE_STUDY.md)
- [Challenge Definition of Done](https://github.com/jannekbuengener/Everlast-AI/blob/master/EVERLAST_AI_CHALLENGE_DEFINITION_OF_DONE.md)
- [Review summary and scope decisions](https://github.com/jannekbuengener/Everlast-AI/blob/master/REVIEW_SUMMARY.md)
- [Diverged `main` smoke report](https://github.com/jannekbuengener/Everlast-AI/blob/main/reports/SYNTAX_ERROR_FIX_EVIDENCE.md) and [idle-state screenshot](https://github.com/jannekbuengener/Everlast-AI/blob/main/reports/evidence/idle_state_ui.png)

**Boundaries and open gaps**

- `master` is the current default; `main` contains stronger implementation/runtime language. They are not combined here and neither branch is treated as canonical by name.
- `node --check src/main/main.js` is a syntax check, not a runtime test.
- No finished voice app, full challenge acceptance, demo video, or manual coding claim is made.

### Clipboard-Brudi

**Strongest signal:** reducing a repetitive local prompt handoff to a deterministic operator flow between a person and an externally run CLI agent.

**Good role and requirement matches**

- AI Operations, AI Enablement, Workflow Automation, Agent UX, operator tooling and human-in-the-loop delivery roles.
- Local-first or privacy-sensitive automation, file/path handoff, prompt workflow design, friction reduction and explicit system boundaries.

**Prefer it over Sample Brain, Claire or Traumtänzer when**

- the vacancy asks how agents are introduced into an existing operator workflow;
- deterministic handoff, local files, small UX decisions or avoiding unnecessary AI are more relevant than model capability.

**Do not use it when**

- the requirement is autonomous agent orchestration, model training, LLM evaluation, backend platform engineering or a fully accepted GUI product;
- a role expects the product itself to execute AI. Clipboard-Brudi deliberately delegates execution to the external CLI agent.

**1-sentence version**

> I designed Clipboard-Brudi as a local operator bridge that turns agent selection, prompt saving and file-URI copying into a deterministic human-agent handoff.

**3-sentence version**

> The problem was not a missing model but repeated friction around folders, filenames and paths when working with CLI agents. The local WinForms flow saves a timestamped Markdown prompt and copies its URI; the external agent remains responsible for interpretation and execution. The case demonstrates workflow decomposition, local automation and operator UX, with GUI acceptance still clearly separated from parser and smoke evidence.

**Interview version**

> I would start by saying what I intentionally did not build: another AI layer. The useful product decision was to keep the handoff deterministic and local, so an operator can see exactly which file is passed to an external agent. The current evidence includes PowerShell parser validation and a WARN smoke report; a fresh manual Windows Save/Copy/CLI check is still the next proof step.

**Evidence**

- [Portfolio case study](https://github.com/jannekbuengener/Clipboard-Brudi/blob/main/docs/PORTFOLIO_CASE_STUDY.md)
- [README and quickstart](https://github.com/jannekbuengener/Clipboard-Brudi/blob/main/README.md)
- [Promptboard implementation](https://github.com/jannekbuengener/Clipboard-Brudi/blob/main/src/Promptboard.ps1)
- [Task-9 evidence](https://github.com/jannekbuengener/Clipboard-Brudi/blob/main/reports/TASK9_EVIDENCE.md)

**Boundaries and open gaps**

- No own AI execution, prompt interpretation or multi-agent orchestration is claimed.
- The documented CI contains setup, lint and test placeholders; a green placeholder workflow is not Save/Copy proof.
- Existing UI images are historical and do not establish the current GUI. Interactive Windows acceptance remains open.

### modusmono-blog

**Strongest signal:** translating an abstract creative concept into a navigable React content experience with explicit information architecture.

**Good role and requirement matches**

- Creative Technologist, Creative Product or Experience roles, content/information architecture, UX/product thinking and AI-assisted web prototyping.
- Concept-to-digital-experience delivery, page and content modelling, navigation, search/category filtering and visual asset integration.

**Prefer it over Sample Brain, Claire or Traumtänzer when**

- the vacancy asks for web-based creative technology, editorial/content experiences, information architecture or rapid frontend concept delivery;
- the evaluator needs to see a concrete path from idea to pages, routes and discoverable content.

**Do not use it when**

- the requirement is backend/CMS ownership, production reliability, AI model engineering, visitor-facing AI functionality or a classic software-engineering claim;
- a recruiter needs public repository access. The source repository is private and should be shared deliberately.

**1-sentence version**

> I translated the Modus Mono concept into a React content experience with About context, blog discovery, local content modelling, filtering and an article route.

**3-sentence version**

> The product question was how an abstract idea about reduction and reflection could become a usable digital experience. I modelled the journey from About context to blog discovery and article view, using local cards, categories, tags, images and explicit routes. The build passes, while existing lint errors, the fixed article detail implementation and the absence of a proven CMS or visitor AI keep the claim at concept-to-experience level.

**Interview version**

> I would show the information architecture first: concept and authorship on About, discovery on Blog, then a slug route for detail. I would point out that the visible pages use local data, so the Supabase client does not prove a CMS or active backend. The honest delivery story is AI-assisted web prototyping with a successful build and known lint/content-route gaps.

**Evidence**

- [Portfolio case study (private repository)](https://github.com/jannekbuengener/modusmono-blog/blob/main/docs/PORTFOLIO_CASE_STUDY.md)
- [App routes](https://github.com/jannekbuengener/modusmono-blog/blob/main/src/App.tsx)
- [Blog page and content model](https://github.com/jannekbuengener/modusmono-blog/blob/main/src/pages/Blog.tsx)
- [Blog post route](https://github.com/jannekbuengener/modusmono-blog/blob/main/src/pages/BlogPost.tsx)
- [Build and lint scripts](https://github.com/jannekbuengener/modusmono-blog/blob/main/package.json)

**Boundaries and open gaps**

- The repository is private; provide access or a hosted walkthrough only when appropriate.
- A Supabase client does not prove an active CMS, correct RLS policies or backend security.
- No production publication, reader metrics, six complete detail pages or visitor-facing AI function is claimed.
- `npm run build` passed on 2026-09-17; `npm run lint` still reports three existing errors and nine warnings outside the portfolio documentation change.

## Core case comparison

| Requirement | Strongest core case | What it proves |
|---|---|---|
| Broad product/system thinking, local-first audio workflow | [Sample Brain](https://github.com/jannekbuengener/sample-brain/blob/main/docs/CASE_STUDY.md) | Producer problem, bounded system slices, evaluation and QA |
| Governance, evaluation contracts, authority boundaries | [Claire de Binare](https://github.com/jannekbuengener/Claire_de_Binare/blob/main/docs/PORTFOLIO_CASE_STUDY.md) | Deterministic gates, fail-closed readiness and auditability |
| Responsible AI, safety, privacy and claims | [Traumtänzer](https://github.com/jannekbuengener/traum_taenzer/blob/main/README.md) | Safety-by-design, privacy-by-design and bounded concept-to-system work |
| Multi-agent orchestration | [Agent Orchestration Case](https://github.com/jannekbuengener/gpt-mcp-server/blob/main/docs/PUBLIC_PORTFOLIO_EXCERPT.md) | Bounded lanes, routing and independent evidence validation |

## CASE-ROUTING-MATRIX

| Job requirement | Primary case | Backup case | Why |
|---|---|---|---|
| Product Discovery | Everlast-AI | Sample Brain | Explicit challenge decomposition and time-boxed product decisions |
| Agentic AI | Agent Orchestration Case | Clipboard-Brudi | The orchestration case proves multi-agent routing; Clipboard adds human handoff context without claiming own AI |
| Workflow Automation | Clipboard-Brudi | Sample Brain | Deterministic local handoff and operator flow |
| Evaluation / QA | Sample Brain | Claire de Binare | Concrete test, runtime and benchmark evidence, backed by governance gates |
| Governance | Claire de Binare | Traumtänzer | Strongest evidence/authority and fail-closed boundaries |
| Responsible AI | Traumtänzer | Claire de Binare | Safety, privacy and claims limits are the product contract |
| Creative Tech | modusmono-blog | Sample Brain | Web concept-to-experience first; Sample Brain is the audio/producer backup |
| UX / Product Thinking | Sample Brain | Everlast-AI | Broader workflow proof, with Everlast as focused discovery example |
| Requirements Engineering | Everlast-AI | Sample Brain | Requirement extraction and Definition of Done are explicit |
| Local-first / Privacy | Clipboard-Brudi | Sample Brain | Local file handoff, then local sample data and runtime |
| Rapid prototyping | Everlast-AI | modusmono-blog | Time-boxed voice scope, then concrete web experience |
| Stakeholder / problem translation | Everlast-AI | Sample Brain | Challenge brief translated into a bounded user flow |
| Content / information architecture | modusmono-blog | Sample Brain | Routes, content cards, filters and visual assets are directly visible |

## Usage rules for applications

1. Start with the vacancy requirement, not the project name.
2. Name one primary case and one backup at most; explain the evidence in one sentence.
3. Keep runtime, GUI, CMS, production and adoption claims at the level proven by the linked evidence.
4. Use the core anchors for governance, evaluation, Responsible AI and multi-agent claims even when a targeted case is newer.
5. State AI-assisted implementation where relevant and describe the product/system contribution precisely.
6. For Everlast, disclose the branch divergence whenever implementation maturity is discussed.
7. For Clipboard-Brudi, disclose that the product does not execute AI and that GUI acceptance is still open.
8. For modusmono-blog, disclose private repository access and the absence of a proven CMS or visitor AI.
