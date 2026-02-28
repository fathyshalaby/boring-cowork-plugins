# Command: /parts:discrepancy-report

Generate a receiving discrepancy report for non-conforming material.

## Output Format
```
RECEIVING DISCREPANCY REPORT
DR #: [number] | Date: [date]
PO #: [number] | Vendor: [name]
Part #: [P/N] | Qty Received: [X]

DISCREPANCY TYPE:
☐ Wrong part  ☐ Wrong quantity  ☐ Damage
☐ Failed inspection  ☐ Missing documentation
☐ Wrong revision  ☐ Other: [describe]

DESCRIPTION:
Ordered: [what was expected]
Received: [what was actually received]

DISPOSITION:
☐ Return to vendor (RMA#: [X])
☐ Use as-is (Engineering waiver attached)
☐ Rework  ☐ Scrap

VENDOR NOTIFICATION: [date/method]
COST IMPACT: $[X] (debit memo/freight/labor)

Inspector: _____________ Date: _________
```
