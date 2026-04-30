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

## What Has Become Visible

Recent public-safe work makes the pre-speech path more concrete.

Static Body Shadow checks show that several body-contour candidates remain distinguishable before LLM speech: quiet baseline, fatigue, recovery, stress, mixed stress/recovery, and day/night rhythm do not collapse into one generic label.

A static/shadow evidence chain also preserves boundaries across the pre-speech path:

```text
body contour -> meaning candidate -> passive context -> choice visibility -> choice ownership -> behavior boundary
```

The achievement is inspectability before speech. It is not louder wording, and it is not a claim that private runtime is published here.

## Public Stage

Garmon is currently in a public research preview stage.

This repository explains the idea, boundaries, and planned path toward a small reviewable demo artifact. It is not yet an interactive demo.

## Why This May Matter

This direction may be useful for:

- safer response shaping;
- believable digital characters;
- long-running assistants;
- game or NPC systems;
- robotics interfaces;
- technical review of meaning before speech;
- distinguishing useful prior context from text noise.

The more specific current value is body-contour distinction before final text. If quiet baseline, fatigue, recovery, stress, and rhythm stay separable before speech, the public review surface becomes clearer than a final answer alone.

## Current Public Milestone

Garmon now has a public-safe static/shadow evidence layer.

It shows:

- distinguishable body-contour candidates before speech;
- negative controls that catch forbidden authority leaks;
- static sequence coherence between simple contour transitions;
- preserved boundaries: contours do not become command, memory, speech, behavior, truth, or implementation permission.

The next useful step is a small public artifact that shows this contour distinction and boundary clearly, without exposing private internals.
