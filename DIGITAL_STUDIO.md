# The Ilana McBain Digital Studio

Version 1.0 — approved and in effect. From this point forward, every new document, registry, AI agent, workflow, and project must conform to this architecture unless the Founder formally approves an amendment through the process in CHARTER.md, Article XII. See DIGITAL_STUDIO_BLUEPRINT_v1.0.md for the full reasoning behind this structure and GOVERNANCE_DIAGRAM_v1.0.svg for the one-page canonical diagram.

**Authority:** Approved by Ilana McBain, Founder, under Article XII of CHARTER.md. This document is the current operating specification of the Ilana McBain Digital Studio and may be amended only through the governance process defined by the Charter and GOVERNANCE.md.

## What this document is

CHARTER.md is the constitution: why the Agency exists, and what it will never do. It does not say how a website gets built, how an agent gets approved, or who signs off before something launches. That operational layer is the Digital Studio — the master operating system for the Agency's entire organisation, governing every website, application, AI agent, automation, workflow, book, artwork, marketing campaign, and future business.

Where this document is silent, the Charter governs. Where this document conflicts with the Charter, the Charter wins, and this document must be corrected.

## The mission

To build confidence through understanding by creating truthful, beautiful, and useful systems that help people flourish.

Every painting, book, philosophical essay, workshop, agent, and future business the Studio produces is an instance of this one sentence. It is the test every department below exists to serve, and the standard against which every project is measured before it is allowed to launch.

## The standing principle

Every system we build should reduce unnecessary complexity while increasing human capability.

This gives the Charter's Article IV ("design elegant systems") and Article X (technology as amplification, not replacement) a concrete, checkable test. Of any project, any department can ask: does this make the thing simpler for the person using it, and more capable, at the same time? A project that increases capability but adds complexity beyond what the problem requires has not yet met the Studio's standard.

## The governance stack

```
CHARTER.md            the constitution — why, and what is forbidden
        |
DIGITAL_STUDIO.md      the operating system — mission, principle, lifecycle, gate
        |
DEPARTMENTS            14 standing divisions, each owning folders and registries
        |
REGISTRIES + PROJECTS  the permanent record, and the actual work
```

## Governance note: The Steward

One agent sits outside the department directory below and outside the governance stack diagram's normal flow: The Steward (Agent 001 in 09-ai-agents/agent-registry.md, specified in full at 09-ai-agents/the-steward.md). The Steward reports only to the Founder — not to the Digital Studio, not to AI & Agents, not to any department — and exists to protect the Studio's alignment with CHARTER.md as the organisation grows across decades. It has no authority to manage a project, create content, make a business decision, or overrule anyone; it may only observe, question, document, and raise concerns, directly to the Founder, whenever truthfulness, dignity, an Ethical Boundary, or the Charter itself appears at risk of being compromised. Because it also watches whether every other agent and department stays within its approved authority, it is evaluated and retired only by the Founder — never by AI & Agents, and never by anything it might itself be reviewing.

## Department directory

| Department | Mission | Folders owned | Registries maintained | Operational Coordination |
|---|---|---|---|---|
| Office of the Founder | Exercises Charter authority through the Founder; approves new departments; breaks ties | 00-foundations, GOVERNANCE.md | Decision Log, Department Registry, Audit Log | — |
| Philosophy & Human Understanding | Develops, tests, and refines the ideas that underpin every project across the Studio | 01-philosophy, 14-evidence-and-research | Open Questions Log, Research Log, Evidence Standards Index | Office of the Founder |
| Knowledge & Intelligence | Curates, organises, preserves, and connects the Agency's accumulated knowledge so it remains discoverable, searchable, and useful across decades | 16-knowledge-and-intelligence | Knowledge Base, Glossary, Pattern Library, Case Studies, Lessons Learned | Digital Studio |
| Founder & Voice | Maintains Ilana's public-facing biography, voice, and body of work | 02-founder | Works Index, Public Statements Registry | Office of the Founder |
| Brand & Communications | Governs how the Agency sounds and how it reaches people | 03-brand-and-voice, 10-marketing-and-communications, 11-community | Campaign Registry, Channel Registry, Community Guidelines Log | Digital Studio |
| Education | Converts philosophy into learners' own lived capability | 04-education | Workshop & Course Registry, Learning Outcomes Log | Digital Studio |
| Publishing | Produces and stewards books and written works | 05-publishing | Publication Registry, Rights & Permissions Registry | Digital Studio |
| Creative Studio | Produces creative work — fine art, design, exhibitions, licensing, and creative direction — as a direct instrument of understanding | 06-creative-studio | Project & Exhibition Registry, Licensing Registry | Digital Studio |
| Digital Products | Builds and maintains every website and application | 07-websites, 08-software | Website & Application Registry, Architecture Decision Log | Digital Studio |
| AI & Agents | Builds and constrains every AI agent; a horizontal capability, not a silo | 09-ai-agents | Agent Registry, Evaluation & Incident Log | Digital Studio |
| Automation & Workflows | The connective tissue moving work between departments without manual re-triggering | tools/, 08-software/internal-tools | Automation Registry | Digital Studio |
| Operations & Business | Keeps the organisation itself running: legal, finance, people, vendors | 12-operations | People & Roles Registry, Vendor & Partner Registry | Office of the Founder |
| Strategy | Long-term vision and cross-department prioritisation, including future businesses | 13-strategy | Roadmap, Risk Register, Metrics Log | Office of the Founder |
| Archive (standing function) | Preserves retired work and the reasoning behind retiring it | 15-archive | Archive Index | Office of the Founder |

templates/ is shared infrastructure, not a department — the Charter Compliance Checklist and every future reusable instrument live there, available to all departments equally.

Automation & Workflows is a horizontal department. Unlike functional departments, it exists to coordinate work across the Studio rather than own a discrete operational domain. Accordingly, it owns no dedicated numbered folder. Instead, it operates through shared infrastructure such as tools/ and 08-software/internal-tools. This is an explicit architectural decision and does not establish a precedent for any future department.

## The project lifecycle

Every website, application, agent, automation, book, campaign, workshop, or artwork the Studio produces moves through the same five stages, regardless of size. Skipping a stage is a Studio failure, not a shortcut.

Intake. The project is named, its owning department is assigned, and its purpose is written down in one honest sentence: what human confidence-building outcome does this serve, per the mission above? If that sentence cannot be written honestly, the project does not proceed.

Compliance review. The project is checked against the Charter Compliance Checklist (templates/charter-compliance-checklist.md) before a single line of production code, copy, or agent prompt is finalized.

Build. The project is built to the standard of the standing principle above and the relevant department's own standards. Decisions of consequence are recorded, not left to memory.

Launch. The project goes live only once the compliance checklist is fully passed and signed. Launch is recorded in the relevant registry.

Maintenance and retirement. Every live project has an owner responsible for it remaining Charter-compliant over time, not merely at launch. When a project is retired, it moves to 15-archive/ with a short note on why.

## The Charter Compliance Gate

No website, application, agent, automation, book, campaign, workshop, or artwork may launch without passing templates/charter-compliance-checklist.md. This is the mechanism that makes the Charter's Non-Negotiables and Ethical Boundaries enforceable in practice, not merely aspirational in principle. The checklist is owned by the Studio rather than by whoever is building a given project, so the person under the most pressure to ship is never the sole judge of whether shipping is safe.

## The Registry Directory

A registry, register, or index is a standing, authoritative list of every live instance of something. The governing rule: if something exists in the Studio and is not in one of the eighteen below, it does not yet officially exist. This is what lets the organisation scale across decades without the Founder personally tracking every individual project.

**Registries, Registers & Indexes (18)** — Department Registry · Public Statements Registry · Campaign Registry · Channel Registry · Workshop & Course Registry · Publication Registry · Rights & Permissions Registry · Project & Exhibition Registry · Licensing Registry · Website & Application Registry · Agent Registry · Automation Registry · People & Roles Registry · Vendor & Partner Registry · Risk Register · Evidence Standards Index · Works Index · Archive Index

**Decision Logs (2)** — the permanent record of decisions made, not merely activity performed: Decision Log · Architecture Decision Log

**Operational Logs (6)** — chronological records of things that happened, distinct from decisions taken: Open Questions Log · Research Log · Community Guidelines Log · Learning Outcomes Log · Evaluation & Incident Log · Metrics Log

**Knowledge Records (5)** — curated, cumulative bodies of understanding rather than indexes of live instances: Knowledge Base · Glossary · Pattern Library · Case Studies · Lessons Learned

**Strategic Records (1)** — Roadmap

**Audit Records (1)** — Audit Log (00-foundations/decision-log/audit-log.md). Every formal audit of the Studio, architectural or otherwise, is indexed here so that audits remain permanent, discoverable institutional memory rather than orphan documents that exist once and are never referenced again.

## Decision rights

Day-to-day decisions within a department belong to whoever owns that department. Decisions that would establish a new department, retire an existing one, or change the project lifecycle itself are recorded in 00-foundations/decision-log/ and require the Founder's sign-off. Any decision that would cross a Non-Negotiable or Ethical Boundary is not a decision the Studio has authority to make at all, regardless of who proposes it — that boundary is not the Studio's to move.

AI agents operating anywhere within the Studio carry the full obligations of the Charter's Article XI. An agent may recommend a project, a design, or an architecture; it may not approve its own compliance checklist, launch a project unattended, or waive a Charter requirement it finds inconvenient.

## Growth principles

Folder numbers are permanent identifiers, not a tidy sequence to be reshuffled. A new department gets the next available number; existing numbers are never reassigned, even if a department is retired, so that references made years ago still resolve. A new department may be created only by a Decision Log entry approved by the Office of the Founder. Every registry follows one canonical format. (templates/registry-template.md defines that canonical format.) Nothing is deleted — retirement moves a thing to the Archive with its reasoning, so the organisation can always answer why it stopped doing something rather than simply forgetting it happened.

## Amending this document

Unlike the Charter, this document may be revised by whoever holds Founder-delegated authority over Studio operations, since it describes operating mechanics rather than governing principle. Every revision is recorded in 00-foundations/decision-log/, and any revision that would weaken the Compliance Gate or narrow a Non-Negotiable or Ethical Boundary requires the Founder's direct approval, treated with the same weight as a Charter amendment.
