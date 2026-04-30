# One-Minute Example

Note: this is an explanation example, not an interactive demo.

## The Problem

An LLM can write useful text, but it is often hard to see what happened before the text was written.

Two things can stay hidden:

- what the event meant before speech;
- whether different body-contour states stayed distinct before speech.

Garmon studies this pre-speech layer.

## Example 1: Event Reading

Event:

> A tense message arrives, and the user wants to answer without making the situation worse.

## Plain Text-Task Shape

The system treats the message as a writing task.

The answer may be polite and useful, but the meaning-before-speech step is not visible.

## Garmon-Shaped Public Example

A small public reading happens before final wording.

The event may be read as:

    lower intensity, keep contact without pressure, avoid escalation

Then a response direction is selected:

    calm boundary reply

The LLM speech layer writes the final answer from that direction.

## What This Shows

It may show a clearer review surface:

    event -> public event reading -> response direction -> final answer

The useful point is not that the final wording is nicer.

The useful point is that the meaning-before-speech step becomes easier to inspect.

## Example 2: Body-Contour Distinction

After the Body Shadow work, another public-safe example is visible.

Different body-contour candidates can be compared before speech:

    quiet baseline -> stable low-pressure contour
    fatigue -> low-energy warning contour
    recovery -> downshift / return contour
    stress -> tension after event contour
    night/downshift -> body-time downshift contour
    day/wake support -> body-time wake-support contour

## Plain Label Shape

A simpler system might flatten these into one vague label:

    low energy / changed state

That would hide the difference between quiet baseline, fatigue, recovery, stress, and rhythm.

## Garmon-Shaped Body-Contour Example

A Body Shadow artifact asks a narrower question:

    do these contours stay distinct before speech?

The current public-safe achievement is that these contours can be inspected without collapsing into one generic label.

## What This Does Not Show

It does not show:

- a finished product;
- an interactive public demo;
- live behavior;
- a new trained language model;
- subjective experience;
- mature autonomy;
- general intelligence;
- external validation;
- memory influence on choice;
- behavior authority from body contours.

## Why This Matters

The useful question is not whether the LLM can write nice text.

The useful question is whether the pre-speech layer can be made easier to inspect.

For Garmon, this now includes both:

- event reading before final speech;
- body-contour distinction before final speech.
