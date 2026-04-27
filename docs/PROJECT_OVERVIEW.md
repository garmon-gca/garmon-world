# Project Overview

Garmon is an early R&D prototype for studying behavior selection around LLM-based agents.

The project does not treat the LLM as the whole agent. The LLM is used as a speech layer. The behavior path around it is studied separately: context traces, runtime signals, boundaries, and small behavior decisions should be visible enough to review.

## Core Idea

Many LLM agent systems mix instruction text, context, tool calls, role descriptions, and final speech inside one large prompt flow.

Garmon explores a stricter question:

> what happens if the final words are written by an LLM, but the agent's behavior is prepared by a separate, auditable runtime path?

This does not make a strong claim about the nature of the agent. It is an engineering and research direction.

## Why This May Matter

This separation may be useful for:

- safer agent behavior;
- believable digital characters;
- long-running assistants;
- game or NPC agents;
- robotics interfaces;
- technical review of agent behavior;
- distinguishing useful context from text noise.

## Current Public Milestone

The project has early internal evidence of short behavior distinctions in controlled local review.

The public interpretation is intentionally cautious:

- this is early;
- it is not enough for strong claims;
- the causal path still needs a reproducible public demo;
- independent review is still needed.

The next useful step is a small reproducible demo that shows behavior differences and reviewable runtime signals without exposing private internals.
