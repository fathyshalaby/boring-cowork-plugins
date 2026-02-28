# Command: /cleaner:inventory-order

Generate a supply inventory check and reorder list.

## Output Format
```
SUPPLY INVENTORY & ORDER
Facility: [name] | Date: [date]

CURRENT INVENTORY:
Item                    On Hand    Par Level    Reorder?    Qty to Order
──────────────────────────────────────────────────────────────────────────
Paper Towels (cases)    [X]        [X]          [Y/N]       [X]
Toilet Paper (cases)    [X]        [X]          [Y/N]       [X]
Trash Liners (cases)    [X]        [X]          [Y/N]       [X]
[etc. for all supplies]

CHEMICALS:
[Same format for cleaning chemicals, disinfectants, etc.]

EQUIPMENT STATUS:
[Condition notes for key equipment items]

ESTIMATED ORDER TOTAL: $[X]
SUPPLIER: [name] | PO#: [number]
```
