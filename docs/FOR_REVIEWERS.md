# For Reviewers

This page is for technical readers who want to understand what can be reviewed without access to private internals.

The public review goal is simple: look at the achievement first, then check whether the boundary is clear.

## What To Review

Useful review areas:

- whether the Body Shadow achievement is understandable;
- whether body-contour distinction before speech is a useful review surface;
- whether the public framing is clear and modest;
- whether the body-born meaning idea is understandable;
- whether the event-reading step is clearly not a fixed label or command;
- whether the LLM speech layer is clearly separated from the step before speech;
- whether the proposed artifact direction is meaningful;
- whether the safety boundaries are strong enough;
- whether the evaluation questions are testable;
- whether the project avoids claims that are too strong.

## Main Technical Questions

The central public questions are:

> can a small public artifact show that body-contour candidates remain distinct before final LLM speech?

and:

> can a small public example make the meaning of an event before final LLM speech easier to inspect?

The first question is currently the stronger first-artifact direction because Body Shadow is the clearest public-safe achievement so far.

This is not a request to accept a conclusion. It is a request to help shape better public artifacts.

Reviewers should evaluate the public review surface, not assume that the private mechanism is fully published. See [Public engineering contracts](PUBLIC_ENGINEERING_CONTRACTS.md).

## Useful Feedback

Helpful feedback includes:

- whether the Body Shadow / body-contour wording is understandable;
- whether the boundary between contour and command stays clear;
- whether the achievement-first framing works;
- what a minimal body-contour artifact should show;
- what a later event-reading demo should show;
- what a minimal demo or artifact should not claim;
- what public summaries should include;
- what public summaries should avoid;
- what comparison tests would be fair;
- what wording would be clearer or safer.

## What Not To Expect Yet

This repository does not yet provide:

- an interactive public demo;
- a production service;
- a complete technical paper;
- third-party validation;
- production deployment instructions;
- private implementation details.

## Suggested First Review Pass

1. Read `README.md`.
2. Read `docs/PUBLIC_CURRENT_STATUS.md`.
3. Read `docs/PUBLIC_BODY_SHADOW_CHECKS.md`.
4. Read `docs/PUBLIC_ENGINEERING_CONTRACTS.md`.
5. Read `docs/ONE_MINUTE_EXAMPLE.md`.
6. Check whether the Body Shadow achievement is understandable to an outside engineer.
7. Check whether the boundary is clear: body contours do not become command, memory, behavior, speech, truth, or implementation permission.
8. Suggest one small test or artifact that could make body-contour distinction easier to evaluate.
9. Check whether the later event-reading demo plan is still understandable after the Body Shadow update.
