---
name: licensed-dispensary-margins
description: Audit operator-supplied licensed dispensary sales and stock reports without placing orders.
---

# Licensed dispensary evidence analysis

1. Confirm operator authorization, store, export dates, currency, taxes and data schema.
2. Use local user-supplied reports only. Do not connect to Dutchie or any live POS account.
3. Separate gross sales, discounts, voids, returns, taxes and net revenue according to documented column meanings.
4. Calculate product margin only with supported COGS, quantities and price. Flag unknown or stale costs.
5. Keep transaction status, unit conversion, missing rows and negative balances distinct.
6. Produce a source-cited discrepancy ledger and prioritized operator verification steps; do not make consumer purchasing recommendations.
