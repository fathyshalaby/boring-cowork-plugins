# Command: /food:recall-trace-prep

Generate a mock recall exercise template.

## Output Format
```
MOCK RECALL EXERCISE
Date: [date] | Conducted By: [name]

SCENARIO: [Description of simulated recall situation]
Target Lot Code: [code] | Product: [name]

TRACEBACK (One Step Back):
Ingredient    Supplier    Lot Code     Received    Qty
──────────────────────────────────────────────────────
[ingredient]  [supplier]  [lot]        [date]      [qty]

TRACEFORWARD (One Step Forward):
Customer      Ship Date    Invoice#    Qty Shipped    Qty Recovered
───────────────────────────────────────────────────────────────────
[customer]    [date]       [#]         [qty]          [qty]

RESULTS:
Total Product in Lot: [X lbs/units]
Total Accounted For: [X] ([X]%)
Time to Complete: [X hours]

Target: 100% within 4 hours
Result: ☐ Pass ☐ Fail
Corrective Actions: [if fail, what needs to improve]
```
