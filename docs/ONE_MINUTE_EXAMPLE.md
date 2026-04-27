# One-Minute Example

## The Problem

Most LLM agents can produce good text, but it is often hard to see what behavior was selected before the text was written.

## Small Example

User task:

> I need to answer a tense message without making the situation worse.

## Prompt-Only Shape

The LLM writes a polite answer directly.

The output may be useful, but the behavior choice is not visible.

## Garmon-Style Shape

A small behavior-preparation step first selects:

```text
selected_behavior: calm_boundary_reply
```

Public reason:

> The task asks for a reply that avoids increasing tension.

Then the LLM speech layer writes the final answer from that behavior.

## What This Shows

It may show a clearer review surface:

```text
input -> selected behavior -> public reason -> final answer
```

## What This Does Not Show

It does not show:

- a finished product;
- a new trained language model;
- subjective experience;
- mature autonomy;
- general intelligence;
- external validation.

## Why This Matters

The useful question is not whether the LLM can write nice text.

The useful question is whether behavior before speech can be made easier to inspect.
