# For Reviewers

This page is for technical readers who want to understand what can be reviewed publicly without access to private internals.

The public review goal is simple:

> look at the achievement first, then check whether the boundary is clear.

Garmon World does not publish the private mechanism.

It publishes a public-safe review surface: the idea, current public-safe evidence, boundaries, and artifact direction.

## Main Public Idea

Garmon studies answer origin before speech.

A compact public frame is:

```text
state -> body contour -> meaning -> choice boundary -> trace -> speech
```

This means the final answer is not treated as the whole system.

The LLM is treated as the speech layer: it writes final words, but it is not presented as the whole system or as the source of choice.

The main question for review is:

> can part of the path before final speech be made visible, bounded, and understandable?

## Current Public-Safe Achievement

The clearest current public-safe achievement is **Body Shadow**.

Body Shadow shows that several body-contour candidates can remain distinguishable before final LLM speech.

Public-safe examples include:

- quiet baseline;
- fatigue;
- recovery;
- stress;
- mixed stress/recovery;
- day/night rhythm.

These contours do not collapse into one generic label.

This is the first achievement to review.

The achievement is not that body contours become commands.

The achievement is that body-contour distinction becomes inspectable before speech.

## Current Public-Safe Chain

The public materials also describe a closed static choice boundary chain:

```text
body contour
-> meaning candidate
-> passive context
-> choice visibility boundary
-> choice ownership boundary
-> behavior boundary
-> pre-selected result boundary candidate (synthetic)
```

This chain is a bounded review surface.

It does not claim public live choice.

It does not claim an actual selected result.

It does not claim public live behavior.

Correct public meaning:

```text
boundary named
boundary not opened
```

The synthetic pre-selected result boundary candidate marks the door before selected result.

It does not open that door.

## What To Review

Useful review areas include:

- whether answer origin before speech is understandable;
- whether the Body Shadow achievement is understandable;
- whether body-contour distinction before speech is a useful review surface;
- whether the public framing is clear and achievement-aware;
- whether the body-born meaning idea is understandable;
- whether the event-reading step is clearly not a fixed label or command;
- whether the LLM speech layer is clearly separated from the step before speech;
- whether the boundary between internal state, meaning, memory, behavior, truth, evidence, and speech is clear;
- whether memory or residue is clearly framed as trace, not hidden motor;
- whether speech is clearly not framed as the source of choice;
- whether visibility is clearly not treated as authority;
- whether evidence is clearly not treated as permission;
- whether the proposed artifact direction is meaningful;
- whether the safety boundaries are strong enough;
- whether the evaluation questions are reviewable;
- whether the project avoids claims that are too strong;
- whether the project also avoids sounding empty or overly defensive.

## Main Technical Questions

The central public questions are:

> Can a small public artifact show that body-contour candidates remain distinct before final LLM speech?

and:

> Can a small public example make the meaning of an event before final LLM speech easier to inspect?

A broader review question is:

> Can Garmon explain a pre-speech path without turning that path into a claim of live choice, behavior, consciousness, life, or mature autonomy?

The first question is currently the strongest first-artifact direction because Body Shadow is the clearest public-safe achievement so far.

This is not a request to accept a conclusion.

It is a request to help shape better public artifacts.

Reviewers should evaluate the public review surface, not assume that the private mechanism is fully published.

See [Public engineering contracts](PUBLIC_ENGINEERING_CONTRACTS.md).

## Useful Feedback

Helpful feedback includes:

- whether the Body Shadow / body-contour wording is understandable;
- whether the boundary between contour and command stays clear;
- whether the boundary between meaning candidate and selected result stays clear;
- whether the boundary between memory/trace and chooser authority stays clear;
- whether the boundary between speech and choice stays clear;
- whether the boundary between evidence and permission stays clear;
- whether the achievement-first framing works;
- what a minimal body-contour artifact should show;
- what a later event-reading demo should show;
- what a minimal demo or artifact should not claim;
- what public summaries should include;
- what public summaries should avoid;
- what comparison tests would be fair;
- what wording would be clearer or safer;
- where the text may sound too strong, too vague, too defensive, or too abstract.

A good review improves clarity without asking for private disclosure.

## What Not To Expect Yet

This repository does not yet provide:

- an interactive public demo;
- a production service;
- a complete technical paper;
- third-party validation;
- production deployment instructions;
- private implementation details;
- live/runtime proof;
- actual selected results;
- public live choice;
- public memory influence on choice;
- public proof of consciousness;
- public proof of life;
- public proof of mature autonomy.

This does not make the repository empty.

It means the current public claim is intentionally bounded.

## What Review Should Not Require

A useful public review should not require:

- private project material;
- raw internal logs;
- local machine paths;
- credentials or tokens;
- protected internal identifiers;
- unpublished working notes;
- exact private implementation details;
- private diagnostic material;
- private runtime material;
- private configuration material;
- private review artifacts;
- any private mechanism description that would allow reconstruction of the closed contour.

The public surface should be reviewed as a public-safe explanation and artifact plan.

It should not be treated as full disclosure of the private system.

## Suggested First Review Pass

1. Read `README.md`.
2. Read `docs/PUBLIC_CURRENT_STATUS.md`.
3. Read `docs/PUBLIC_BODY_SHADOW_CHECKS.md`.
4. Read `docs/PUBLIC_ENGINEERING_CONTRACTS.md`.
5. Read `docs/PUBLIC_MEMORY_RESIDUE_BOUNDARIES.md`.
6. Read `docs/ONE_MINUTE_EXAMPLE.md`.
7. Check whether the Body Shadow achievement is understandable to an outside technical reader.
8. Check whether the boundary is clear: body contours do not become command, memory, behavior, speech, truth, selected-result authority, runtime proof, or implementation permission.
9. Check whether memory/residue is clearly described as trace, not active live authority.
10. Check whether speech is clearly described as the LLM layer after response direction, not as the source of choice.
11. Check whether the pre-selected result boundary candidate is clearly synthetic and closed.
12. Suggest one small public artifact that could make body-contour distinction easier to evaluate.
13. Check whether a later event-reading demo plan is still understandable after the Body Shadow update.

## Boundary Checklist For Reviewers

When reviewing any public Garmon material, ask:

- Does this imply live behavior from static/shadow evidence?
- Does this imply actual selected results?
- Does this imply memory or residue already drives live choice?
- Does this imply speech creates choice?
- Does this imply visibility is authority?
- Does this imply evidence is permission?
- Does this imply a report is decision truth?
- Does this imply public evidence proves consciousness, life, subjectivity, or mature autonomy?
- Does this expose private implementation details?
- Does this make the achievement clearer without making the claim stronger?
- Does this make the boundary clearer without making the project sound empty?
- Does this keep supported evidence, theory, and open hypothesis separate?

## Public Artifact Questions

A useful first public artifact should answer questions like:

- Can the same public-safe event be shown under different body contours?
- Can quiet baseline, fatigue, recovery, stress, mixed stress/recovery, and rhythm remain distinguishable?
- Can a meaning candidate or response direction be shown without becoming selected result?
- Can negative controls show that forbidden authority leaks are caught?
- Can the artifact stay small enough to review?
- Can it avoid pretending to be a full interactive demo?
- Can it avoid private implementation details?

The artifact should make the current achievement easier to inspect.

It should not make the public claim larger than the evidence.

## How To Give Feedback

Good feedback is:

- specific;
- calm;
- public-safe;
- focused on one issue at a time;
- clear about what a reader may misunderstand;
- careful about the difference between wording, evidence, theory, and future work.

Good examples:

> The phrase “choice chain” may sound like live choice. “Choice boundary chain” may be safer.

> The Body Shadow section is understandable, but the boundary that contours are not commands should appear closer to the achievement.

> The README explains the idea well, but the difference between memory as trace and memory as authority could be simpler.

> A first artifact could compare one event across quiet baseline, fatigue, recovery, and stress.

Less useful feedback:

> Publish the private mechanism.

> Show all internal logs.

> Prove consciousness.

> Make it a live demo immediately.

> Remove all boundaries because they weaken the claim.

## What A Good Review Helps Preserve

A good review helps preserve both sides:

- Garmon is not empty.
- Garmon is not overclaimed.

The current public materials should show a real achievement:

> distinguishable body-contour candidates before speech.

They should also preserve the central boundary:

> distinguishable contours do not become command, memory, behavior, truth, speech authority, selected-result authority, runtime proof, or implementation permission.

## One-Line Summary

The best review right now is narrow and technical: check whether Body Shadow and the pre-speech review surface are understandable, whether the boundaries remain clear, and what small public artifact would make the current achievement easiest to evaluate.
