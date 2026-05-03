<p align="center">
  <img src="assets/brand/garmon-world-mark.svg" alt="Garmon World" width="120">
</p>

# Garmon World

**Garmon** is an early research prototype for studying how internal state can shape meaning, response direction, and the first visible boundaries of behavior before an LLM writes the final answer.

Garmon is not presented here as a finished agent, product, biological system, conscious system, or autonomous system.

This repository is a public research preview. It explains the idea, the current public-safe evidence, and the boundaries that must stay clear.

## Plain-Language Version

Garmon studies what happens before an LLM writes a final answer.

In a normal chatbot, the system often starts from the text request and generates a reply.

Garmon explores a different layer: first, the system reads the input as an event through an internal state model, for example quiet baseline, stress, fatigue, recovery, or mixed states. That event reading forms a response direction. Only after that does the LLM turn the direction into words.

This is what this repository calls **body-born meaning before LLM speech**.

This is a working public term. It does not mean biological life, subjective experience, or a claim of consciousness. It means that an event is interpreted through an internal-state layer before final speech.

The broader direction is to study how a line of behavior can be shaped before speech, while keeping the boundaries between meaning, choice, memory, behavior, truth, and speech explicit.

## Core Idea

In many AI projects, a request is treated mainly as a text task:

```text
request -> analysis -> plan -> answer
```

Garmon explores a different question:

> what if the request is first treated as an event that meets an internal state?

The public idea is modest. The LLM writes the final words, but the path before speech should not be reduced to prompt text alone.

In this repository, **pre-speech** means the layer before the LLM writes the final answer.

**Body-born meaning** means that the event is interpreted through an internal state model before final speech.

A simplified public chain looks like this:

```text
internal state -> event reading -> response direction -> LLM speech -> final answer
```

A broader working direction behind Garmon is:

```text
internal state -> meaning -> choice boundary -> time/residue -> speech
```

This second chain is not a public claim of live choice. It is a research direction: meaning, memory, choice, and speech should not be collapsed into one text-generation step.

The useful question is simple:

> can an internal-state-shaped interpretation be made visible and bounded before final LLM speech?

For readers familiar with AI safety, agent design, or LLM systems, this can be understood as research around a pre-generation layer of an LLM-based system.

The repository does not present Garmon as a finished agent, product, biological system, conscious system, or autonomous system.

## Working Direction Behind Garmon

Garmon grew from a practical problem: convincing speech is not the same as a stable line of behavior.

A system can answer clearly, politely, and intelligently, while still restarting its behavioral line from session to session. A prompt can restore style, role, or instructions, but a prompt alone does not create a continuing internal state.

Garmon explores a different framing:

- speech should express a path, not replace it;
- internal state should shape how an event is read;
- meaning should appear before final wording;
- memory should act as residue, not as a hidden motor;
- choice-related boundaries should be protected from speech, memory, reports, and external commands;
- evidence should help avoid self-deception, but evidence is not the same as truth or autonomy.

This is not a claim that Garmon is conscious or alive.

It is a research direction inside Garmon: to study whether behavior can be organized before speech, with visible boundaries and reviewable evidence.

## One-Minute Example

A tense message arrives.

Plain text-task shape:

- the system treats the message as a request to write a polite reply;
- the final answer may be useful;
- the step where the event receives its meaning is not visible.

Garmon-shaped public example:

- the system first reads the event through an internal state model;
- that reading forms a response direction, such as lowering intensity or keeping contact without pressure;
- the LLM speech layer writes the final words from that direction.

Point:

> the claim is not "smarter text"; the point is a more visible meaning-before-speech step.

For the short standalone version, see [One-minute example](docs/ONE_MINUTE_EXAMPLE.md).

## Current Public-Safe Achievement

Garmon now has a static/shadow evidence layer around **Body Shadow**, and the first static choice chain has been closed as public-safe evidence.

Static checks show that several body-contour candidates remain distinguishable before LLM speech: quiet baseline, fatigue, recovery, stress, mixed stress/recovery, and day/night rhythm do not collapse into one generic label.

The achievement is not louder wording. The achievement is a more inspectable and bounded pre-speech layer: body contours can move toward meaning candidates and passive context while preserving the boundary that contours do not become command, memory, speech, behavior, truth, or implementation permission.

A recent synthetic update extends the passive chain to a **pre-selected result boundary candidate**. This means the path from body to the door just before an actual selected result is now marked, but the door remains closed.

There is still **no** public claim of a selected result, live choice, behavior, memory influence, application authority, or runtime proof.

For the current status, see [Public current status](docs/PUBLIC_CURRENT_STATUS.md). For the Body Shadow summary, see [Public Body Shadow checks](docs/PUBLIC_BODY_SHADOW_CHECKS.md).

## Why This Matters

The immediate public value of Garmon is not that it produces more dramatic answers.

The value is that part of the path before speech becomes easier to inspect.

If quiet baseline, fatigue, recovery, stress, mixed states, and rhythm remain distinguishable before speech, then the system is not only producing final text. It is also exposing a reviewable pre-speech surface.

This matters because many difficult questions in AI behavior are hidden if we only inspect the final answer.

Garmon tries to keep these boundaries clear:

```text
state is not command
meaning is not behavior
memory is not chooser
speech is not will
evidence is not truth
visibility is not authority
```

These boundaries are central to the project.

## Current Status

- Public research preview: yes.
- Static/shadow evidence layer: Body Shadow, the static choice-chain closure, and the passive chain reaching a pre-selected result boundary candidate are now summarized publicly.
- Interactive public demo: not yet.
- Public docs: yes.
- Internal prototype: exists, but this repository only contains public-facing materials.
- Public evidence: limited public-safe summaries.
- Next step: minimal reviewable public artifact.

This repository is a public research preview. It explains the idea, boundaries, and path toward a small reviewable artifact. It is not yet an interactive demo.

## What To Read First

1. [Project overview](docs/PROJECT_OVERVIEW.md)
2. [Public current status](docs/PUBLIC_CURRENT_STATUS.md)
3. [Public Body Shadow checks](docs/PUBLIC_BODY_SHADOW_CHECKS.md)
4. [Public engineering contracts](docs/PUBLIC_ENGINEERING_CONTRACTS.md)
5. [Public memory and residue boundaries](docs/PUBLIC_MEMORY_RESIDUE_BOUNDARIES.md)
6. [One-minute example](docs/ONE_MINUTE_EXAMPLE.md)

The most useful feedback right now is about clarity, safety of claims, and how to make the first public artifact easy to review.

## What Garmon Does Not Claim

Garmon does not claim to be:

- a finished product;
- a new trained language model;
- general intelligence;
- biological life;
- subjective experience;
- mature autonomy;
- externally validated;
- an interactive public demo;
- a system with public live behavior;
- a system with actual selected results;
- a public proof of consciousness;
- a public proof of life.

The current public framing is modest but no longer empty:

> Garmon is an early research prototype for studying how different internal-state contours can shape meaning before final LLM speech while remaining separate from command, memory, behavior, truth, and implementation authority.

## Author and Working Style

Garmon is created by Vitaliy, an independent self-taught builder whose work is driven by practical review cycles, direct discussion, and AI-assisted drafting and safety checks.

The project has been developed through practical work, repeated boundary reviews, static/shadow checks, negative controls, and AI-assisted engineering review.

AI tools may help with translation, drafts, structure, and safety review. Vitaliy remains responsible for project direction, public claims, and publication decisions.

## Contact

For now, this repository is a calm public entry point. More contact details and demo materials may be added later.

## Public Artifact Status

The next public artifact is planned as a small, reviewable body-contour distinction artifact.

It should stay public-safe: no private implementation details, no raw logs, no local paths, no runtime internals, and no claim of live choice or actual selected results.

Until that artifact is ready, the repository should be read as a public research preview with bounded static/shadow evidence, not as a runnable public demo.

## Additional Materials

The most important pages are listed above. More public-safe notes are available below.

<details>
<summary>Show all public materials</summary>

- [Russian overview](docs/RU_OVERVIEW.md)
- [FAQ](docs/FAQ.md)
- [Public FAQ in Russian](docs/PUBLIC_FAQ_RU.md)
- [Public glossary](docs/GLOSSARY_PUBLIC.md)
- [Public current status](docs/PUBLIC_CURRENT_STATUS.md)
- [Public Body Shadow checks](docs/PUBLIC_BODY_SHADOW_CHECKS.md)
- [Public engineering contracts](docs/PUBLIC_ENGINEERING_CONTRACTS.md)
- [Public memory and residue boundaries](docs/PUBLIC_MEMORY_RESIDUE_BOUNDARIES.md)
- [Demo brief](docs/DEMO_BRIEF.md)
- [First public demo plan](docs/FIRST_PUBLIC_DEMO_PLAN.md)
- [Review questions](docs/REVIEW_QUESTIONS.md)
- [Feedback request](docs/FEEDBACK_REQUEST.md)
- [Roadmap](docs/ROADMAP.md)
- [Evidence note: first safe contact](docs/EVIDENCE_NOTE_FIRST_SAFE_CONTACT.md)
- [Public release checklist](docs/PUBLIC_RELEASE_CHECKLIST.md)
- [Public readiness review](docs/PUBLIC_READINESS_REVIEW.md)
- [Opening post draft](docs/OPENING_POST_DRAFT.md)
- [Contact](docs/CONTACT.md)
- [Contributing](CONTRIBUTING.md)
- [Security](SECURITY.md)
- [License status](docs/LICENSE_STATUS.md)

</details>
