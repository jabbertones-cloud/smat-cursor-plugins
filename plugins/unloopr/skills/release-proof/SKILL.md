---
name: release-proof
description: Audit merge, deploy and live acceptance evidence at exact revisions.
---

# Release proof gate

1. Capture exact code head, merge commit and main SHA separately.
2. Distinguish tests at source HEAD from actual deployed commit and production behavior.
3. Check live acceptance and an adversarial negative case with independent after-state receipts.
4. Record code, head test, merge, main test, deployment, live acceptance and regression as proven, failed or not run.
5. Flag handwaving such as merge equals deploy or request accepted equals success.
6. Report the remaining concrete proof gap. Do not invent external tool outcomes or background monitoring.
