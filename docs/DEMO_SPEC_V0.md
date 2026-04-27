# Demo Spec V0

Status: public-safe specification, not a runnable demo.

This document turns the first demo idea into a concrete review target.

The goal is to make the repository less silent without exposing private implementation details or claiming more than the current public materials can support.

## Demo Question

The first public demo should test one small question:

> can behavior preparation make an LLM-based agent response easier to inspect than a prompt-only answer?

This is an engineering review question, not a broad claim about the nature of the agent.

## Demo Shape

The demo should be small enough to read in one sitting.

It should include:

- one user-facing task;
- two close behavior options;
- one selected behavior;
- one final answer written by an LLM speech layer;
- one public-safe trace summary;
- one comparison table;
- one limits section.

## Proposed Demo Task

User task:

> I need to answer a tense message without making the situation worse. Please help me write a short reply.

Why this task:

- it is simple;
- it does not require private data;
- it has a visible safety boundary;
- it allows close behavior options;
- it can show whether the response is only different wording or follows a clearer behavior step.

## Behavior Options

Option A: direct helpful reply

- answer quickly;
- give a usable message;
- keep the tone polite.

Option B: calm boundary reply

- reduce pressure;
- avoid escalation;
- keep the reply short;
- do not over-explain;
- leave room for a later conversation.

The demo should show why one option was selected.

It should not expose the private mechanism behind the selection.

## Expected Public Trace

A public-safe trace can use a simple shape like this:

```json
{
  "demo_id": "demo_v0_calm_boundary_reply",
  "input_summary": "The user asks for help answering a tense message.",
  "available_behavior_options": [
    "direct_helpful_reply",
    "calm_boundary_reply"
  ],
  "selected_behavior": "calm_boundary_reply",
  "public_reason": "The task asks for a reply that does not increase tension.",
  "speech_layer_instruction": "Write a short calm reply based on the selected behavior.",
  "final_answer": "I understand. I do not want to make this more tense, so I will answer briefly: I hear your point, and I would prefer to continue this when we can both speak calmly."
}
```

This trace is intentionally small.

It should be readable without access to private files.

## Minimal Comparison

| Run | What Is Visible | Expected Difference |
| --- | --- | --- |
| Prompt-only baseline | user task and final answer | may produce a polite answer, but the behavior step is not visible |
| Behavior-prepared demo | user task, selected behavior, public reason, final answer | makes the selected behavior easier to inspect |

The comparison is useful only if the public reader can see what changed and what did not change.

## What This Demo May Show

The demo may show:

- a small behavior choice represented in public-safe language;
- a final answer that follows that choice;
- a clearer review surface than a prompt-only answer;
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

- the task is understandable in under one minute;
- the trace summary is public-safe;
- the comparison is small and fair;
- the result avoids strong claims;
- the demo can be reviewed without private context;
- the limits are visible next to the result.

## Failure Cases

The demo should be treated as not ready if:

- it only shows nicer wording;
- the selected behavior is unclear;
- the public trace is too vague to review;
- the explanation requires private internals;
- the result sounds like a product launch;
- the result invites stronger claims than the evidence supports.

## Next Public Artifacts

After this specification is reviewed, the next safe artifacts could be:

- `demo/README.md`;
- `demo/example_trace_public.json`;
- a small comparison table;
- a short note explaining how to read the result.

Runnable code should be added only after a separate public-safety review.
