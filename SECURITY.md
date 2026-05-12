# Security and Public Boundary

Garmon World is a public-facing research repository.

Its security model is not only about credentials, tokens, or conventional software vulnerabilities. It is also about preserving the public boundary of Garmon: what can be safely described, what must remain private, and what must not be overstated.

This repository should contain only public-safe material:

- core ideas;
- public positioning;
- claim boundaries;
- current public status;
- reviewable summaries;
- public-safe evidence notes;
- documentation-level explanations.

It must not publish private project material, private implementation details, raw internal material, credentials, or protected working notes.

## Public Boundary Principle

Garmon studies the order in which an artificial answer may receive an origin before speech.

That idea can be discussed publicly.

The protected working contour must not be exposed as public mechanism.

A public explanation should show the principle, not reveal protected internals.

A public document may describe the layered order:

```text
state -> body contour -> meaning -> choice boundary -> trace -> speech
```

But it must not expose private project material, local paths, raw internal logs, protected internal identifiers, private configuration material, private runtime material, or exact implementation details.

The public surface should be strong, understandable, and reviewable without becoming a technical leak.

## Do Not Share Private Material

Please do not open issues, pull requests, comments, discussions, or attachments containing:

- private project material;
- raw internal logs;
- local machine paths;
- credentials;
- tokens;
- cookies;
- private headers;
- environment variables;
- unpublished working notes;
- exact private implementation details;
- protected internal identifiers;
- protected internal evidence material;
- private runtime material;
- private diagnostic material;
- private configuration material;
- private review artifacts;
- any private mechanism description that would allow reconstruction of the closed contour.

If a concern requires private context, do not paste the private material into a public GitHub issue.

Describe the concern at a high level instead.

Good public form:

> This document may expose more implementation detail than needed for a public explanation.

Bad public form:

> Here is private material and the exact mechanism that caused the issue.

## Reporting a Public-Safety Concern

If you notice that a public document seems too detailed, too strong, unclear, or misaligned with Garmon’s boundaries, please open a careful issue using the review feedback template.

Useful reports include:

- unclear public wording;
- a claim that sounds stronger than the public evidence supports;
- static or shadow evidence framed as live behavior;
- Body Shadow framed as command authority;
- body contours framed as memory, truth, behavior, final speech, or action;
- memory or residue framed as active live authority;
- meaning candidates framed as selected results;
- pre-selected boundary language framed as an actual selected result;
- speech framed as the source of choice;
- evidence framed as permission to open a higher layer;
- reports framed as decision truth;
- public summaries that may reveal too much private mechanism;
- a missing boundary note;
- wording that could confuse public evidence with private runtime behavior.

The best report is specific, calm, and boundary-focused.

Example:

> The phrase “selected result” may sound like public live choice. Consider changing it to “pre-selected result boundary candidate.”

## Reporting a Conventional Security Concern

This repository does not currently expose a production service, public API, runnable public system, or interactive public demo.

If that changes, this security policy should be updated.

For now, most issues will be documentation-boundary concerns rather than conventional software security bugs.

Still, if you find exposed credentials, private material, accidental internal details, or anything that should not be public, report it immediately and avoid copying the sensitive content into a public issue.

Instead, describe the problem safely:

> A public file appears to contain a token-like value.

Do not post the token itself.

## What This Repository Must Keep Clear

Public Garmon materials should preserve these boundaries:

- internal state is not command authority;
- body contour is not behavior;
- meaning candidate is not selected result;
- memory or residue is not a hidden motor;
- speech is not the source of choice;
- evidence is not decision truth;
- visibility is not authority;
- static/shadow evidence is not live runtime proof;
- report is not decision;
- trace is not owner;
- public summary is not private implementation disclosure;
- public research preview is not a product launch;
- public status is not proof of consciousness, life, mature autonomy, or public live choice.

These boundaries are not defensive disclaimers.

They are part of the architecture.

## What Is Not Helpful

Please avoid reports that demand private disclosure in order to make the public explanation more convincing.

For example:

- “Publish the internal logs to prove it.”
- “Show the private runtime path.”
- “Expose the exact implementation.”
- “Release the hidden mechanism.”
- “Show the raw traces.”
- “Make the public summary more impressive by adding internal details.”

Garmon’s public language should be strong enough to explain the idea without turning the repository into a private technical dump.

## Response Style

Reports will be handled carefully.

The first response may clarify a boundary rather than publish more detail.

A public-safety issue may be resolved by:

- softening a claim;
- making a boundary more explicit;
- replacing private detail with a public-safe summary;
- removing accidental internal material;
- separating supported evidence from theory or open hypothesis;
- changing wording that gives a layer more authority than it has.

The goal is to keep the public surface useful, reviewable, and honest without exposing private implementation details or overstating what current public evidence shows.

## Summary

Security for Garmon World means two things:

1. Do not expose private material.
2. Do not let public language give the wrong layer the wrong authority.

A public document is safe when it helps readers understand the idea without leaking the private contour and without claiming more than the public material can hold.
