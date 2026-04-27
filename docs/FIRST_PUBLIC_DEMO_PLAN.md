# First Public Demo Plan

This document describes the intended first public demo for Garmon.

The demo is not ready yet. This is a public-safe plan for what the first demo should and should not show.

## Purpose

The first demo should make one narrow question easier to review:

> can a small agent setup show a behavior difference that is easier to inspect than a plain prompt-only answer?

The goal is not to prove a big claim. The goal is to create a modest, reproducible starting point for technical feedback.

## What The Demo Should Include

The first demo should include:

- one short task;
- two close behavior options;
- the final answer selected by the demo;
- a public-safe trace summary;
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

- what the input was;
- what output was selected;
- what changed between close options;
- what the result might suggest;
- what the result does not prove.

## Minimal Comparison

A useful first comparison could be:

- run the same small task without the behavior layer;
- run it with the public-safe behavior layer;
- compare whether the selected answer changes in a meaningful and repeatable way.

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

- input;
- output;
- trace summary;
- comparison note;
- limits.

Only after that should code or runnable material be added.
