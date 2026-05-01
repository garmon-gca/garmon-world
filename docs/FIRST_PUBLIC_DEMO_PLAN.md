# First Public Demo Plan

This document describes the intended first public artifact path for Garmon.

The first public artifact does not have to be an interactive demo. It may first be a small, public-safe body-contour artifact that shows the current Body Shadow achievement.

## Purpose

The first public artifact should make one narrow question easier to review:

> can a small public artifact show that body-contour candidates remain distinct before final LLM speech?

A later event-reading artifact can test a second question:

> can a small public example show how an event receives meaning before final LLM speech?

The goal is not to prove a big claim. The goal is to create a modest, reproducible starting point for technical feedback.

## Current Best First Artifact

The strongest first public artifact is currently a body-contour distinction artifact.

It should show that several body-contour candidates remain distinguishable before speech:

- quiet baseline;
- fatigue;
- recovery;
- stress;
- mixed stress/recovery;
- night/downshift;
- day/wake support.

The useful point is not stronger wording. The useful point is a more inspectable pre-speech layer.

## What The First Artifact Should Include

The first body-contour artifact should include:

- a small set of body-contour candidates;
- one public-safe reading for each contour;
- a small comparison note;
- a clear boundary section;
- a short limits section.

A later event-reading artifact may include:

- one short visible event;
- two close response directions;
- a final answer following the response direction used by the demo;
- a public-safe summary;
- a comparison note;
- a short limits section.

## What The Artifact Should Avoid

The artifact should avoid:

- private implementation details;
- raw local logs;
- private markers;
- internal file paths;
- internal report filenames;
- protected identifiers;
- unpublished working notes;
- claims that are stronger than the result.

## Reviewable Output

The output should be readable without knowing the private project.

An outside reviewer should be able to see:

- which body-contour candidates are being compared;
- what public-safe reading is attached to each contour;
- whether the contours stay distinct;
- what the result might suggest;
- what the result does not prove.

For a later event-reading artifact, an outside reviewer should be able to see:

- what the event was;
- what final answer followed the response direction used;
- what changed between close response directions;
- what the result might suggest;
- what the result does not prove.

## Minimal Comparison

A useful first comparison could be:

- show quiet baseline, fatigue, recovery, stress, and rhythm as separate body-contour candidates;
- give each one a small public-safe reading;
- check whether they stay distinct or collapse into one generic label.

A later event-reading comparison could be:

- show the same small event as a direct text task;
- show it as a Garmon-shaped public example with an event-reading step;
- compare whether the final answer follows a clearer public direction.

Both comparisons should stay small. A tiny repeatable check is better than a large unclear demo.

## Success Criteria

The first public artifact is useful if:

- it is easy to inspect;
- it does not expose private internals;
- the body-contour distinction is understandable;
- it avoids strong claims;
- it produces a clear next technical question;
- it can be improved after review.

## Failure Criteria

The artifact is not ready if:

- it depends on private files;
- it only shows different wording;
- body-contour differences collapse into vague labels;
- it requires trust in hidden steps;
- it sounds like a finished product;
- it cannot be repeated or inspected by an outside reader.

## Boundary

The first public artifact must not imply:

- live behavior;
- memory;
- truth;
- final speech;
- behavior authority;
- command authority;
- implementation permission;
- a life-status claim.

## Next Action

The next action is to design the smallest public-safe body-contour artifact:

- contour set;
- public-safe readings;
- comparison note;
- boundary section;
- limits.

Only after that should runnable code, interactive demo material, or event-reading demo code be considered.
