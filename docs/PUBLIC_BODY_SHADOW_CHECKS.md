# Public Body Shadow Checks

Status:
This is a public-safe summary of static Body Shadow checks. It does not publish private implementation details.

## What Has Been Shown

Garmon now has a small public-safe achievement: static Body Shadow checks distinguish several body-contour candidates before LLM speech.

The checked contours include:

- quiet baseline;
- neutral body state;
- fatigue;
- recovery;
- stress;
- mixed stress/recovery;
- night/downshift;
- day/wake support;
- calm-body request context;
- tense-body request context.

The important result is that these contours do not collapse into one generic label.

## Why This Matters

This supports the central Garmon direction:

```text
state -> meaning -> choice -> speech
```

The achievement is not stronger wording. The achievement is a more inspectable pre-speech layer where body-contour differences can be reviewed before final text is written.

## Negative Controls

The checks also include negative controls.

That means deliberately invalid cases are expected to fail. This is important because a useful public-safe check must be able to go green for valid candidate contours and red when a forbidden authority leak is introduced.

In public terms: the harness can distinguish a valid contour summary from a contour trying to become command, memory, behavior, truth, speech, or runtime authority.

## Sequence Coherence

Static sequence checks also show that body-contour candidates can move coherently across simple transitions, such as:

- quiet baseline -> stress -> recovery;
- fatigue -> recovery;
- night/downshift -> day/wake support;
- stress -> mixed stress/recovery.

This is still a static review surface, not a live timeline.

## Boundary

Body Shadow checks do not publish the private mechanism.

They do not create:

- command authority;
- behavior authority;
- memory;
- decision truth;
- speech authority;
- live interaction;
- implementation permission.

## One-Line Summary

Body Shadow gives Garmon its first public-safe body-contour distinction surface: different pre-speech contours can be inspected without becoming commands.
