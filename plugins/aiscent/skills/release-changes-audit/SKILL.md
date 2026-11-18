---
name: release-changes-audit
description: Prepare evidence-backed App Store update notes from local commits and release artifacts.
---

# Release changes audit

1. Identify last shipped version/tag, target version/build and exact repository SHA from available evidence.
2. Review actual diff, release notes, issue history and local test receipts.
3. Distinguish implemented, merged, locally tested, deployed and live-verified changes.
4. Extract customer-facing verified changes, preserving feature names and platform constraints.
5. Identify unsupported claims and missing evidence before writing update metadata.
6. Create a release notes draft, per-locale translation review queue and blocker report; do not claim ASC submission.
