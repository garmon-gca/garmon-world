<p align="center">
  <img src="assets/brand/garmon-world-mark.svg" alt="Garmon World" width="120">
</p>

# Garmon World

**Garmon** is an early R&D prototype exploring a behavior-preparation layer around LLM-based agents.

Most LLM agents mix instructions, context, goals, safety, and final speech inside one prompt flow. Garmon explores a cleaner split: a small step prepares what kind of behavior is appropriate before the LLM writes the final words.

```text
User input -> behavior preparation -> selected behavior -> LLM speech -> final answer
```

The useful question is simple:

> can behavior before speech be made easier to inspect?

## One-Minute Example

User asks:

> I need to answer a tense message without making the situation worse.

Prompt-only baseline:

- the LLM writes a polite reply directly;
- the answer may be useful;
- the behavior step is hidden.

Garmon-style demo:

- the system first selects a public behavior such as `calm_boundary_reply`;
- the public reason is visible: the task asks for a reply that avoids increasing tension;
- the LLM speech layer writes the final text from that selected behavior.

Point:

> the claim is not "smarter text"; the point is a more visible behavior step before text.

For the short standalone version, see [One-minute example](docs/ONE_MINUTE_EXAMPLE.md).

## Current Status

- Public docs: yes.
- Runnable public demo: not yet.
- Private prototype: exists, but is not published here.
- Public evidence: limited public-safe note.
- Next step: minimal reproducible demo artifact.

This repository is a quiet public entry point for understanding the project and shaping the first reviewable demo.

## What To Read First

1. [Project overview](docs/PROJECT_OVERVIEW.md)
2. [One-minute example](docs/ONE_MINUTE_EXAMPLE.md)
3. [Public boundaries](docs/PUBLIC_BOUNDARIES.md)
4. [Demo spec V0](docs/DEMO_SPEC_V0.md)
5. [For reviewers](docs/FOR_REVIEWERS.md)

The most useful feedback right now is about clarity, safety of claims, and how to make the first demo easy to review.

## What Garmon Does Not Claim

Garmon does not claim to be:

- a finished product;
- a new trained language model;
- general intelligence;
- subjective experience;
- mature autonomy;
- external validation.

The current public framing is modest:

> Garmon is an early research prototype for studying reviewable behavior selection around LLM agents.

## Author And Working Style

Garmon is created by Vitaliy, an independent builder learning through practice, discussion, and AI-assisted work.

AI tools may help with translation, drafts, structure, and safety review. Vitaliy remains responsible for project direction and publication decisions.

## Additional Materials

- [Russian overview](docs/RU_OVERVIEW.md)
- [FAQ](docs/FAQ.md)
- [Публичный FAQ на русском](docs/PUBLIC_FAQ_RU.md)
- [Public glossary](docs/GLOSSARY_PUBLIC.md)
- [Demo brief](docs/DEMO_BRIEF.md)
- [First public demo plan](docs/FIRST_PUBLIC_DEMO_PLAN.md)
- [Review questions](docs/REVIEW_QUESTIONS.md)
- [Roadmap](docs/ROADMAP.md)
- [Evidence note: first safe contact](docs/EVIDENCE_NOTE_FIRST_SAFE_CONTACT.md)
- [Public release checklist](docs/PUBLIC_RELEASE_CHECKLIST.md)
- [Public readiness review](docs/PUBLIC_READINESS_REVIEW.md)
- [Opening post draft](docs/OPENING_POST_DRAFT.md)
- [Contact](docs/CONTACT.md)
- [Contributing](CONTRIBUTING.md)
- [Security](SECURITY.md)
- [License status](docs/LICENSE_STATUS.md)

## Contact

For now, this repository is a calm public entry point. More contact details and demo materials may be added later.
