# Demo Spec V0

Status: public-safe specification, not a runnable demo.

This specification describes a future reviewable demo artifact. It is not an interactive product demo and does not provide user interaction with Garmon.

This document turns the first demo idea into a concrete review target.

The goal is to make the repository less silent without exposing private implementation details or claiming more than the current public materials can support.

For a shorter first-reading version, see [One-minute example](ONE_MINUTE_EXAMPLE.md).

The demo artifact should expose the public review surface, not the private mechanism.

## Demo Question

The first public demo should test one small question:

> can a public example show how an event receives meaning before final LLM speech?

After the Body Shadow work, a second useful review question is now visible:

> can a public artifact show that body-contour candidates remain distinct before speech without becoming command authority?

These are engineering review questions, not broad claims about the nature of the system.

## Demo Shape

The demo should be small enough to read in one sitting.

It may use one of two public-safe shapes:

1. event-reading artifact;
2. body-contour distinction artifact.

Both shapes should keep the private implementation out of the public repository.

## Shape A: Event-Reading Artifact

This shape should include:

- one visible event or task;
- two close response directions;
- one response direction used;
- one final answer written by an LLM speech layer;
- one public-safe summary;
- one comparison note;
- one limits section.

### Proposed Demo Event

Visible event:

> A tense message arrives, and the user wants to answer without making the situation worse.

Why this event:

- it is simple;
- it does not require private data;
- it has a visible safety boundary;
- it allows close response directions;
- it can show whether the answer only changes wording or follows a clearer meaning-before-speech step.

### Response Directions

Direction A: direct helpful reply

- answer quickly;
- give a usable message;
- keep the tone polite.

Direction B: calm boundary reply

- reduce pressure;
- avoid escalation;
- keep the reply short;
- do not over-explain;
- leave room for a later conversation.

The demo should show why one response direction was used.

It should not expose the private mechanism behind the choice.

The public event reading should stay modest: it is a reviewable summary, not a fixed label and not a command.

## Shape B: Body-Contour Distinction Artifact

This shape may be a better first public artifact than an interactive chat demo.

It should show that body-contour candidates can remain distinct before final speech.

A small artifact may compare:

- quiet baseline;
- fatigue;
- recovery;
- stress;
- mixed stress/recovery;
- night/downshift;
- day/wake support.

The useful public question is:

> do these contours stay distinct, or do they collapse into one generic label?

This artifact should show body-contour distinction and its boundary side by side.

It should not imply that a contour creates behavior, memory, truth, speech authority, or implementation permission.

## Expected Public Summary

A public-safe event-reading summary can use a simple shape like this:

```json
{
  "demo_id": "demo_v0_event_meaning",
  "event_summary": "A tense message arrives, and the user wants to answer without increasing tension.",
  "candidate_response_directions": [
    "direct helpful reply",
    "calm boundary reply"
  ],
  "response_direction_used": "calm boundary reply",
  "public_event_reading": "The event calls for lower pressure and a bounded answer.",
  "speech_layer_task": "Write a short reply following the response direction used."
}
```

A public-safe body-contour artifact can use a smaller review table instead of a full response example:

```text
quiet baseline -> stable low-pressure contour
fatigue -> low-energy warning contour
recovery -> downshift / return contour
stress -> tension after event contour
mixed stress/recovery -> partial recovery under remaining pressure
night/downshift -> body-time downshift contour
day/wake support -> body-time wake-support contour
```

This summary is intentionally small.

It should be readable without access to private files.

It should not be read as the full private path. It is only the public surface needed for review.

The demo artifact must not imply that a public event reading is memory or residue.

## Minimal Comparison

A useful comparison should show three things:

- the visible event or contour set;
- the public-safe reading attached to it;
- the boundary that prevents the reading from becoming command, memory, behavior, truth, or final speech.

For event-reading examples, the comparison should make clear whether the final answer follows a public direction rather than merely being nicer wording.

For body-contour examples, the comparison should make clear whether quiet baseline, fatigue, recovery, stress, and rhythm remain distinguishable before speech.

## What This Demo May Show

The demo may show:

- a small event reading represented in public-safe language;
- a final answer that follows a response direction;
- a clearer review surface before final text;
- distinguishable body-contour candidates before speech;
- a starting point for technical feedback.

## What This Demo Must Not Claim

The demo must not claim:

- a finished product;
- a new trained language model;
- subjective experience;
- mature autonomy;
- general intelligence;
- external validation;
- access to private implementation details;
- live interaction;
- memory influence on choice;
- behavior authority from body contours.

## Private Boundary

The demo must not include:

- private workbench files;
- raw logs;
- local machine paths;
- private markers;
- exact private control details;
- unpublished working notes;
- private evidence packages;
- internal report filenames;
- protected identifiers;
- private owner paths.

If a detail is needed only to make the result look stronger, it should stay out.

## Acceptance Criteria

The demo spec is ready to become a demo artifact only if:

- the event or contour set is understandable in under one minute;
- the public summary is safe;
- the comparison is small and fair;
- the result avoids strong claims;
- the demo can be reviewed without private context;
- the limits are visible next to the result;
- the artifact shows achievement first and boundary second.

## Failure Cases

The demo should be treated as not ready if:

- it only shows nicer wording;
- the event reading is unclear;
- body-contour differences collapse into vague labels;
- the public summary is too vague to review;
- the explanation requires private internals;
- the result sounds like a product launch;
- the result invites stronger claims than the evidence supports.

## Next Public Artifacts

After this specification is reviewed, the next safe artifacts could be:

- a small body-contour distinction table;
- a public-safe example summary;
- a small comparison note;
- a short note explaining how to read the result.

Runnable code should be added only after a separate public-safety review.
