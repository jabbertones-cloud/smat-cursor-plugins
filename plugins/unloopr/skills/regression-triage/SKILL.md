---
name: regression-triage
description: Analyze local failing tests, diffs and repeated repair attempts using evidence-first code review.
---

# Regression and incident triage

1. Identify repo, expected behavior, failing repro, affected environment, current HEAD and previous known-good SHA.
2. Trace the smallest relevant diff and history, including previous failed repair attempts.
3. Distinguish triggering defect from secondary symptoms and unverified pattern matches.
4. For standard libraries or primitives, compare maintained upstream donors with pinned source, tests and license before suggesting bespoke code.
5. Propose a falsifiable repair hypothesis, focused regression test and rollback condition.
6. Report exact commands, sources and test outcomes; do not claim unrun CI or perform edits without user authorization.
