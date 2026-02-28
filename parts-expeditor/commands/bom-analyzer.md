# Command: /parts:bom-analyzer

Generate a BOM shortage analysis for a production order.

## Output Format
```
BOM SHORTAGE ANALYSIS
Assembly: [P/N] | Qty Required: [X]
Need Date: [date]

Part#      Description    Qty/Assy  Total Need  On Hand  On Order  Short  ETA
────────────────────────────────────────────────────────────────────────────────
[P/N]      [desc]         [X]       [X]         [X]      [X]       [X]    [date]

CRITICAL SHORTAGES (blocking production):
[Parts list with recovery plan]

LONG-LEAD ITEMS:
[Parts with lead time >4 weeks]

RECOMMENDATION:
☐ All parts available — production can proceed
☐ Partial shortages — production can start with workaround
☐ Critical shortage — production blocked until [date]
```
