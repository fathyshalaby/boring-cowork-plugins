# Command: /parts:status-chase

Generate an order status chase report for outstanding purchase orders.

## Output Format
```
ORDER STATUS REPORT
Date: [date] | Expeditor: [name]

OUTSTANDING ORDERS:
PO#      Vendor       Part#         Qty    Due Date    Status       Action
────────────────────────────────────────────────────────────────────────────
[PO]     [vendor]     [P/N]         [X]    [date]      [On track/Late/At risk]  [action]

CRITICAL SHORTAGES:
[Parts at risk of causing production delay]

PREMIUM FREIGHT AUTHORIZED:
[Orders requiring expedited shipping — PO#, cost, justification]

ESCALATIONS NEEDED:
[Issues requiring management intervention]
```
