# 0001. Record decisions in the repository

- **Date:** 2026-10-22
- **Status:** Accepted

## Context

This project involves many choices about tools, security and trade-offs. Without a written record, the reasons are easy to forget, and they are exactly what is needed when explaining or revisiting the work.

## Decision

Keep short decision records in `docs/decisions/`, one numbered Markdown file per decision, based on `0000-template.md`. An accepted record is not edited when the decision changes. A new record supersedes it instead.

## Consequences

- The reasoning behind each choice is versioned together with the code.
- Writing a record costs a few minutes per decision.
- Records must be kept free of secrets and real identifiers, because the repository is public.

## Alternatives considered

- **Notes outside the repository:** easy to lose, and invisible to anyone reading the project.
- **Explaining everything in the README:** the README would grow quickly and mix current facts with history.
