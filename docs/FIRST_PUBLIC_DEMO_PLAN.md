# First Public Demo Plan

This document describes the intended first public demo for Garmon.

The demo is not ready yet. This is a public-safe plan for what the first demo should and should not show.

## Purpose

The first demo should make one narrow question easier to review:

> can a small public example show how an event receives meaning before final LLM speech?

The goal is not to prove a big claim. The goal is to create a modest, reproducible starting point for technical feedback.

## What The Demo Should Include

The first demo should include:

- one short visible event;
- two close response directions;
- the final answer selected by the demo;
- a public-safe summary;
- a comparison note;
- a short limits section.

## What The Demo Should Avoid

The demo should avoid:

- private implementation details;
- raw local logs;
- private marker values;
- internal file paths;
- unpublished working notes;
- claims that are stronger than the result.

## Reviewable Output

The output should be readable without knowing the private project.

An outside reviewer should be able to see:

- what the event was;
- what final answer was selected;
- what changed between close response directions;
- what the result might suggest;
- what the result does not prove.

## Minimal Comparison

A useful first comparison could be:

- show the same small event as a direct text task;
- show it as a Garmon-shaped public example with an event-reading step;
- compare whether the final answer follows a clearer public direction.

This comparison should stay small. A tiny repeatable check is better than a large unclear demo.

## Success Criteria

The demo is useful if:

- it is easy to run or inspect;
- it does not expose private internals;
- it avoids strong claims;
- it produces a clear next technical question;
- it can be improved after review.

## Failure Criteria

The demo is not ready if:

- it depends on private files;
- it only shows different wording;
- it requires trust in hidden steps;
- it sounds like a finished product;
- it cannot be repeated by an outside reader.

## Next Action

The next action is to design the smallest public-safe demo artifact:

- event;
- final answer;
- public-safe summary;
- comparison note;
- limits.

Only after that should code or runnable material be added.
