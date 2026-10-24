# Decision records

Use one Markdown file per significant technical decision. Name files `0001-short-title.md`, `0002-short-title.md`, and so on. Record the decision when it is made, including the reason and tradeoffs. Small implementation details can stay in code and pull requests.

Each record should use this format:

```md
# NNNN: Decision title

Date: YYYY-MM-DD
Status: Proposed | Accepted | Superseded by NNNN

## Context

What problem or constraint prompted the decision?

## Decision

What was chosen?

## Consequences

What becomes easier, harder, or required as a result?
```

If an accepted decision changes, add a new record and mark the old one as superseded. Keep product requirements in `../spec.md`.
