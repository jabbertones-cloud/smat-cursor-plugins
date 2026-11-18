---
name: fba-reimbursement-evidence
description: Reconcile FBA loss and reimbursement exports without making unsupported money-owed claims.
---

# FBA and reimbursement evidence reconciliation

1. Pin account, marketplace, source dates, currencies and seller SKU/FNSKU identifiers before analysis.
2. Separate loss events, provider receipts, reimbursement events, adjustments and reversals. Use event IDs, not product names alone, to join.
3. Report gross units, reversed units, net observed units and amounts only where evidence supports each value.
4. Deduplicate records by actual source identifiers; retain links to each original source.
5. Never infer Amazon owes money merely because gross shipments and refunds differ. Mark unmatched evidence and uncertainty.
6. Produce a reconciliation table with exact sources, conflicts and independent verification steps. Never file support cases or change seller data.
