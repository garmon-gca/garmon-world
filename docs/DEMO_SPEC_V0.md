# Demo Spec V0

Status: public-safe specification, not a runnable demo.

This specification describes a future reviewable demo artifact. It is not an interactive product demo and does not provide user interaction with Garmon.

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

This shape should include one visible event or task, two close response directions, one response direction used, one final answer written by an LLM speech layer, one public-safe summary, one comparison table, and one limits section.

### Proposed Demo Event

Visible event:

> A tense message arrives, and the user wants to answer without making the situation worse.

Direction A: direct helpful reply.

Direction B: calm boundary reply.

The demo should show why one response direction was used. It should not expose the private mechanism behind the choice.

The public event reading should stay modest: it is a reviewable summary, not a fixed label and not a command.

## Shape B: Body-Contour Distinction Artifact

This shape may be a better first public artifact than an interactive chat demo.

It should show that body-contour candidates can remain distinct before final speech.

A small artifact may compare quiet baseline, fatigue, recovery, stress, night/downshift, and day/wake support.

The useful public question is:

> do these contours stay distinct, or do they collapse into one generic label?

This artifact should show body-contour distinction and its boundary side by side.

It should not imply that a contour creates behavior, memory, truth, speech authority, or implementation permission.

## Expected Public Summary

```json
{
  "demo_id": "demo_v0_event_meaning",
  "event_summary": "A tense message arrives, and the user wants to answer without increasing tension.",
  "candidate_response_directions": ["direct helpful reply", "calm boundary reply"],
  "response_direction_used": "calm boundary reply",
  "public_event_reading": "The event calls for lower pressure and a bounded answer.",
  "speech_layer_task": "Write a short reply following the response direction used."
}
```

A public-safe body-contour artifact can use a smaller review table instead of a full response example.

## What This Demo Must Not Claim

The demo must not claim a finished product, a new trained language model, subjective experience, mature autonomy, general intelligence, external validation, access to private implementation details, live interaction, memory influence on choice, or behavior authority from body contours.

## Private Boundary

The demo must not include private workbench files, raw logs, local machine paths, private marker values, exact private control details, unpublished working notes, private evidence packages, internal report filenames, protected hashes, or private owner paths.
