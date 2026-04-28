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

This is an engineering review question, not a broad claim about the nature of the system.

## Demo Shape

The demo should be small enough to read in one sitting.

It should include:

- one visible event or task;
- two close response directions;
- one selected direction;
- one final answer written by an LLM speech layer;
- one public-safe summary;
- one comparison table;
- one limits section.

## Proposed Demo Event

Visible event:

> A tense message arrives, and the user wants to answer without making the situation worse.

Why this event:

- it is simple;
- it does not require private data;
- it has a visible safety boundary;
- it allows close response directions;
- it can show whether the answer only changes wording or follows a clearer meaning-before-speech step.

## Response Directions

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

The demo should show why one direction was selected.

It should not expose the private mechanism behind the selection.

The public event reading should stay modest: it is a reviewable summary, not a fixed label and not a command.

## Expected Public Summary

A public-safe summary can use a simple shape like this:

```json
{
  "demo_id": "demo_v0_event_meaning",
  "event_summary": "A tense message arrives, and the user wants to answer without increasing tension.",
  "candidate_response_directions": [
    "direct helpful reply",
    "calm boundary reply"
  ],
  "selected_response_direction": "calm boundary reply",
  "public_event_reading": "The event calls for lower pressure and a bounded answer.",
  "speech_layer_task": "Write a short reply following the selected direction.",
  "final_answer": "I understand. I do not want to make this more tense, so I will answer briefly: I hear your point, and I would prefer to continue this when we can both speak calmly."
}
```

This summary is intentionally small.

It should be readable without access to private files.

It should not be read as the full private path. It is only the public surface needed for review.

## Minimal Comparison

| Run | What Is Visible | Expected Difference |
| --- | --- | --- |
| Direct text-task baseline | visible event and final answer | may produce a polite answer, but the event reading is not visible |
| Garmon-shaped public example | visible event, response direction, public event reading, final answer | makes the meaning-before-speech step easier to inspect |

The comparison is useful only if the public reader can see what changed and what did not change.

## What This Demo May Show

The demo may show:

- a small event reading represented in public-safe language;
- a final answer that follows a response direction;
- a clearer review surface before final text;
- a starting point for technical feedback.

## What This Demo Must Not Claim

The demo must not claim:

- a finished product;
- a new trained language model;
- subjective experience;
- mature autonomy;
- general intelligence;
- external validation;
- access to private implementation details.

## Private Boundary

The demo must not include:

- private workbench files;
- raw logs;
- local machine paths;
- private marker values;
- exact private control details;
- unpublished working notes;
- private evidence packages.

If a detail is needed only to make the result look stronger, it should stay out.

## Acceptance Criteria

The demo spec is ready to become a demo artifact only if:

- the event is understandable in under one minute;
- the public summary is safe;
- the comparison is small and fair;
- the result avoids strong claims;
- the demo can be reviewed without private context;
- the limits are visible next to the result.

## Failure Cases

The demo should be treated as not ready if:

- it only shows nicer wording;
- the event reading is unclear;
- the public summary is too vague to review;
- the explanation requires private internals;
- the result sounds like a product launch;
- the result invites stronger claims than the evidence supports.

## Next Public Artifacts

After this specification is reviewed, the next safe artifacts could be:

- `demo/README.md`;
- `demo/example_summary_public.json`;
- a small comparison table;
- a short note explaining how to read the result.

Runnable code should be added only after a separate public-safety review.
