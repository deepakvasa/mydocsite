---
sidebar_position: 3
---

# Architecture decision record template

This is a sample template for recording architecture decisions. For more information, please refer to [Documenting architecture decisions - Michael Nygard](http://thinkrelevance.com/blog/2011/11/15/documenting-architecture-decisions)

Every new architecture decision will be recored in a new md file with the following naming convention "<000n>-title.md" e.g. "0001-SAML-for-Multitenant-Integration.md" and will be stored under the "adr" folder.

In each ADR file, write these sections:

# Title

These documents have names that are short noun phrases. For example, "ADR 0001: SAML for Multitenant Integration" or "ADR 0009: Deployment on Linux VM"

## Status

What is the status, such as proposed, accepted, rejected, deprecated, superseded, etc.?

A decision may be "proposed" if the project stakeholders haven't agreed with it yet, or "accepted" once it is agreed. If a later ADR changes or reverses a decision, it may be marked as "deprecated" or "superseded" with a reference to its replacement.

## Context

What is the issue that we're seeing that is motivating this decision or change?

This section describes the forces at play, including technological, political, social, and project local. These forces are probably in tension, and should be called out as such. The language in this section is value-neutral. It is simply describing facts.

## Decision

What is the change that we're proposing and/or doing?

This section describes our response to these forces. It is stated in full sentences, with active voice. "We will …"

## Consequences

What becomes easier or more difficult to do because of this change?

This section describes the resulting context, after applying the decision. All consequences should be listed here, not just the "positive" ones. A particular decision may have positive, negative, and neutral consequences, but all of them affect the team and project in the future.

