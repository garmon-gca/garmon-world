# For Reviewers

This page is for technical readers who want to understand what can be reviewed without access to private internals.

## What To Review

Useful review areas:

- whether the public framing is clear and modest;
- whether the body-born meaning idea is understandable;
- whether the LLM speech layer is clearly separated from the step before speech;
- whether the proposed demo direction is meaningful;
- whether the safety boundaries are strong enough;
- whether the evaluation questions are testable;
- whether the project avoids claims that are too strong.

## Main Technical Question

The central public question is:

> can a small public example make the meaning of an event before final LLM speech easier to inspect?

This is not a request to accept a conclusion. It is a request to help shape a better test.

## Useful Feedback

Helpful feedback includes:

- what a minimal demo should show;
- what a minimal demo should not claim;
- what public summaries should include;
- what public summaries should avoid;
- what comparison tests would be fair;
- what wording would be clearer or safer.

## What Not To Expect Yet

This repository does not yet provide:

- a finished runnable demo;
- a complete technical paper;
- third-party validation;
- production deployment instructions;
- private implementation details.

## Suggested First Review Pass

1. Read `README.md`.
2. Read `docs/PUBLIC_BOUNDARIES.md`.
3. Read `docs/DEMO_BRIEF.md`.
4. Check whether the demo plan would be understandable to an outside engineer.
5. Suggest one small test that could make the event-reading step easier to evaluate.
