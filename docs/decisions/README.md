# Decision records

Short notes explaining **why** a choice was made, so the reasoning is still available months later. One decision per file.

## Index

| No. | Decision | Status |
|---|---|---|
| [0001](0001-record-decisions.md) | Record decisions in the repository | Accepted |

## How to add one

1. Copy [`0000-template.md`](0000-template.md) to the next number, for example `0002-short-title.md` (lowercase, words separated by hyphens).
2. Fill in the sections. A few sentences each is enough; one page at most.
3. Add a row to the index above.
4. Do not rewrite an accepted decision when your mind changes. Write a new record, mark the old one `Superseded by NNNN`, and link them.

## Ground rules

- Record choices that were not obvious or that you would otherwise have to re-explain, such as a tool, a trade-off or a security decision.
- Write what was true at the time, including what you did not know yet.
- Never put secrets, real IP addresses or account IDs in a record.
