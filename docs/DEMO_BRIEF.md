# Demo Brief

This is an early public-safe outline for a future Garmon demo.

The demo is not published yet. This document describes the intended direction.

## Goal

The goal is to show a small behavior difference in a controlled setting, while keeping the private implementation out of the public repository.

The demo should help answer:

> did the agent's behavior change in a reviewable way, or did the LLM only produce different wording?

## What The Demo Should Show

A useful public demo should show:

- the user-facing prompt or task;
- the final answer;
- a public-safe trace of the behavior step;
- a comparison between two close options;
- a clear note about what the result does and does not show.

## What The Demo Should Not Show

The demo should not expose:

- private workbench files;
- raw internal logs;
- exact private control details;
- private marker values;
- local machine paths;
- unpublished research notes.

## Expected Public Output

The public output should be small and readable:

- a short task;
- the selected answer;
- a public-safe trace summary;
- a short explanation of the limits;
- a reproducible command or script when ready.

## Success Criteria

The first public demo should be considered useful if:

- an outside reader can run or inspect it;
- the output is small enough to review;
- the claims remain modest;
- the private internals remain private;
- the result suggests a next technical question.

## Non-Goal

The first demo is not meant to prove a big claim.

It is meant to create a calm, reviewable starting point.
