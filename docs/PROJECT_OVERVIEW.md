# Project Overview

Garmon is an early R&D prototype for studying body-born meaning before LLM speech.

The project does not treat the LLM as the whole system. The LLM is used as a speech layer. The path before speech is studied separately: a request is not only a text task, but an event that meets an inner bodily background.

For readers familiar with AI safety, agent design, or LLM systems, this can be read as research around a pre-speech layer of an LLM-based system. Garmon is not presented here as a finished agent or product.

## Core Idea

Many AI systems start from the request and move downward into a plan and an answer.

Garmon explores a stricter question:

> what happens if the final words are written by an LLM, but the event receives a visible embodied meaning before those words are written?

This does not make a strong claim about the nature of the system. It is an engineering and research direction.

In these public notes, body-born meaning means a high-level event-reading step. It is not a biological claim and does not imply subjective experience.

Simple shape:

```text
bodily background -> embodied event meaning -> inclination -> response direction -> LLM speech -> final answer
```

## Public Stage

Garmon is currently in a pre-demo research stage.

This repository is a public research preview: it explains the idea, boundaries, and planned path toward a small reviewable demo. It is not yet an interactive demo.

## Why This May Matter

This direction may be useful for:

- safer response shaping;
- believable digital characters;
- long-running assistants;
- game or NPC systems;
- robotics interfaces;
- technical review of meaning before speech;
- distinguishing useful prior context from text noise.

## Current Public Milestone

The project has early internal evidence of short distinctions in controlled local review.

The public interpretation is intentionally cautious:

- this is early;
- it is not enough for strong claims;
- the public demo path still needs a reproducible artifact;
- independent review is still needed.

The next useful step is a small reproducible demo that shows how an event is read before final speech, without exposing private internals.
