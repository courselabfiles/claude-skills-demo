---
name: meridian-release-checker
description: Use when checking a press release or announcement against a source table of true figures. Verifies every number, flags hedged language, lists issues with locations.
---

# Meridian release checker

## Procedure
1. Read the source table. Note every metric and its true value.
2. Read the release. For each metric in both, compare the stated number to the true value. A digit change, a transposition, or a magnitude shift is a mismatch.
3. Flag hedged language: approximately, we believe, roughly, around, in our view, we think.
4. Do not rewrite the release. Report only. If a number is not in the source table, mark it unverifiable; never assume it is correct.

## Output format
A bullet list, one issue per bullet, giving the type (NUMBER MISMATCH, HEDGED LANGUAGE, or UNVERIFIABLE), the location, and the stated and true values. End with the counts.
