# Public Glossary

This glossary explains public terms used in Garmon World.

It avoids private implementation details.

## LLM speech layer

The part of the system where an LLM writes the final text shown to a user.

In Garmon World, the public idea is that final text and behavior preparation should be discussed as different concerns.

## Behavior preparation

The public term for the step before final text is written.

It means preparing what kind of response or action is appropriate, without treating the prompt text as the only source of behavior.

## Public-safe trace

A small public summary of what happened in a run or review.

It should be readable, modest, and safe to show. It should not include private files, local paths, raw logs, or exact private implementation details.

## Reviewable behavior

Behavior that can be inspected by another person.

For this repository, reviewable behavior means: the input, output, limits, and public-safe summary are clear enough for calm technical feedback.

## Demo plan

A plan for a future small demo.

The demo plan explains what should be shown, what should not be shown, and what the result should not claim.

## Evidence note

A short public-safe summary of an internal review result.

An evidence note is not the raw evidence package. It is a careful summary that keeps private material out of the public repository.

## Public boundary

The line between what can be discussed openly and what should stay private.

For Garmon World, public boundaries protect private files, raw logs, local paths, unpublished working notes, and exact private implementation details.

## Calm technical review

Feedback focused on clarity, safety of claims, reproducibility, and wording.

It is not pressure to make stronger claims.
