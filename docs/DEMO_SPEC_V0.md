# Demo Spec V0

Status: public-safe specification, not a runnable demo.

This document describes a future reviewable public artifact for Garmon.

It is not an interactive product demo.

It does not provide public interaction with Garmon.

The goal is to turn the first demo direction into a concrete review target without exposing private implementation details or making claims stronger than the current public evidence.

For a shorter first-reading version, see [One-Minute Example](ONE_MINUTE_EXAMPLE.md).

The artifact should expose the public review surface, not the protected mechanism.

## Core Demo Questions

The first public artifact should help answer one narrow question:

> can a public example show how an event receives meaning before final LLM speech?

After the Body Shadow work, a second useful review question is now visible:

> can a public artifact show that body-contour candidates remain distinguishable before speech without becoming command authority?

A broader public Garmon direction sits behind these questions:

```text
state -> body contour -> meaning -> choice boundary -> trace -> speech
```

This broader direction is not a public claim of live choice, live behavior, consciousness, life, or mature autonomy.

These are engineering review questions, not broad claims about the nature of the system.

## Demo Philosophy

The first artifact should not try to prove everything.

A small inspectable result is more useful than a large unclear demo.

The first artifact should:

- be understandable quickly;
- expose a narrow review surface;
- preserve the boundary next to the result;
- avoid private internals;
- avoid product-launch framing;
- remain technically honest.

The public law remains:

```text
participation is not power
```

## Two Public-Safe Shapes

The demo direction currently has two useful public-safe shapes:

1. Event-reading artifact.
2. Body-contour distinction artifact.

Both shapes should:

- remain bounded;
- remain reviewable;
- avoid private implementation detail;
- avoid live-choice claims;
- avoid behavior-authority claims;
- avoid sounding like a full public runtime system.

The stronger first public artifact may be Shape B because Body Shadow is currently the clearest public-safe achievement.

## Shape A: Event-Reading Artifact

This shape focuses on meaning before final speech.

It should include:

- one visible event or task;
- two or more close response directions;
- one response direction used;
- one final answer written by the LLM speech layer;
- one public-safe event reading;
- one comparison note;
- one limits section.

The artifact should help reviewers inspect:

```text
event -> reading -> response direction -> speech
```

without exposing the private mechanism.

### Proposed Event

Visible event:

> A tense message arrives, and the user wants to answer without making the situation worse.

Why this event:

- it is simple;
- it avoids private data;
- it has a visible safety boundary;
- it allows close response directions;
- it can show whether the final answer follows a visible direction rather than only generating text directly.

### Example Response Directions

Direction A:

```text
direct helpful reply
```

Possible public-safe traits:

- answer quickly;
- give a usable message;
- keep the tone polite.

Direction B:

```text
calm boundary reply
```

Possible public-safe traits:

- reduce pressure;
- avoid escalation;
- keep the reply short;
- avoid over-explaining;
- leave room for later conversation.

The artifact should show why a response direction was used.

It should not expose the private mechanism behind that direction.

The event reading must stay modest.

It is:

- a reviewable summary;
- not a fixed label;
- not a command;
- not memory;
- not behavior;
- not decision truth.

## Shape B: Body-Contour Distinction Artifact

This shape may be a stronger first artifact than an interactive chat demo.

It focuses on distinguishability before speech.

A small artifact may compare:

- quiet baseline;
- fatigue;
- recovery;
- stress;
- mixed stress/recovery;
- night/downshift;
- day/wake support.

The useful public question is:

> do these contours remain distinct before speech, or collapse into one generic label?

This artifact should show body-contour distinction and its boundary side by side.

It must not imply that contours become:

- command;
- memory;
- behavior;
- truth;
- speech authority;
- selected-result authority;
- runtime proof;
- implementation permission.

## Example Body-Contour Surface

A public-safe comparison could look like:

```text
quiet baseline -> stable low-pressure contour
fatigue -> low-energy caution contour
recovery -> downshift / return contour
stress -> tension after event contour
mixed stress/recovery -> recovery under remaining pressure
night/downshift -> body-time downshift contour
day/wake support -> body-time wake-support contour
```

The useful point is not stronger wording.

The useful point is distinguishability before speech.

## Expected Public Summary

A public-safe event-reading summary may use a simple shape like this:

```json
{
  "demo_id": "demo_v0_event_reading",
  "event_summary": "A tense message arrives, and the user wants to answer without increasing tension.",
  "candidate_response_directions": [
    "direct helpful reply",
    "calm boundary reply"
  ],
  "response_direction_used": "calm boundary reply",
  "public_event_reading": "The event calls for lower pressure and a bounded answer.",
  "speech_layer_task": "Write a short reply following the response direction."
}
```

A public-safe body-contour artifact may use a smaller comparison table instead of a response example.

These summaries are intentionally small.

They should be readable without access to private files.

They should not be treated as the full private path.

## Minimal Comparison

A useful comparison should show three things:

1. the visible event or contour set;
2. the public-safe reading attached to it;
3. the boundary that prevents the reading from becoming command, memory, behavior, truth, final speech, selected-result authority, or implementation permission.

For event-reading examples, the comparison should make clear whether the final answer follows a visible response direction rather than merely becoming nicer wording.

For body-contour examples, the comparison should make clear whether quiet baseline, fatigue, recovery, stress, mixed stress/recovery, and rhythm remain distinguishable before speech.

## Boundary Notes

Every artifact should keep a short boundary note close to the result.

For event-reading artifacts:

```text
event reading is not command
response direction is not selected result
speech is not proof of live choice
```

For body-contour artifacts:

```text
body contour is not command
body contour is not memory
body contour is not behavior
body contour is not truth
body contour is not final speech
```

For both shapes:

```text
static/shadow evidence is not runtime proof
public summary is not the private mechanism
visibility is not authority
evidence is not decision truth
```

The artifact should show the achievement first.

The boundary should remain visible immediately after.

## What This Demo May Show

The artifact may show:

- a small event reading represented in public-safe language;
- distinguishable body-contour candidates before speech;
- a final answer following a response direction;
- a clearer review surface before final text;
- preserved boundaries around command, memory, behavior, truth, and speech;
- a narrow technical starting point for feedback.

## What This Demo Must Not Claim

The artifact must not claim:

- a finished product;
- a new trained language model;
- subjective experience;
- consciousness;
- biological life;
- mature autonomy;
- general intelligence;
- external validation;
- access to the private mechanism;
- live interaction;
- live choice;
- actual selected result;
- memory influence on choice;
- behavior authority from body contours;
- speech as the source of choice;
- runtime proof.

These limits do not weaken the artifact.

They keep the artifact accurate.

## Relation To Memory

The first body-contour artifact should not frame contour distinction as memory.

A body contour is not memory.

A diagnostic trace is not lived residue.

A static/shadow check is not lived experience.

Memory and residue should remain future-gated unless separate evidence and separate boundary review support a narrower claim.

## Relation To Speech

The first body-contour artifact should not make final speech the only visible source of meaning.

The point is to show something before speech.

In event-reading examples, final speech should follow a response direction rather than create the whole meaning after the fact.

Safe framing:

```text
response direction -> speech
```

Unsafe framing:

```text
speech -> choice
speech -> meaning
```

## Private Boundary

The artifact must not include:

- private project material;
- raw internal logs;
- local machine paths;
- protected internal identifiers;
- unpublished working notes;
- private runtime material;
- private diagnostic material;
- private configuration material;
- private review artifacts;
- any mechanism description that would allow reconstruction of the closed contour.

If a detail is needed only to make the result sound stronger, it should stay out.

## Acceptance Criteria

The spec is ready to become an artifact only if:

- the event or contour set is understandable in under one minute;
- the public summary is safe;
- the comparison is small and fair;
- the result avoids strong claims;
- the artifact can be reviewed without private context;
- the limits are visible next to the result;
- the achievement appears before the boundary;
- the artifact does not imply live behavior, actual selected results, memory authority, or speech authority.

## Failure Cases

The artifact should be treated as not ready if:

- it only shows nicer wording;
- the event reading is unclear;
- body-contour differences collapse into vague labels;
- the summary is too vague to review;
- the explanation requires private internals;
- the result sounds like a product launch;
- the result invites stronger claims than the evidence supports;
- the result implies live choice or actual selected results;
- the result implies memory or residue already drives behavior;
- the result makes speech look like the source of choice.

## Next Public Artifacts

After this specification is reviewed, the next useful public artifacts may include:

- a small body-contour distinction table;
- a public-safe event-reading example;
- a small comparison note;
- a short “how to read this artifact” note;
- a short limits note;
- a small negative-control comparison.

Runnable code should be added only after separate public-safety review.

## Final Reminder

The first public artifact should not try to prove the whole theory.

It should open a calm review surface.

Show the achievement.

Keep the boundary visible.

Do not expose the protected mechanism.

Do not make the artifact sound smaller than it is.

Do not make the artifact sound larger than the evidence can hold.

## One-Line Summary

Demo Spec V0 defines two small public-safe artifact shapes — event reading and body-contour distinction — so Garmon can show a reviewable pre-speech surface without exposing private internals or claiming live behavior, memory authority, actual selected results, consciousness, life, or a finished system.
