# Command: /food:supplier-review

Generate a supplier approval evaluation form.

## Output Format
```
SUPPLIER APPROVAL EVALUATION
Supplier: [name] | Date: [date]
Product(s) Supplied: [list]
Risk Level: ☐ High ☐ Medium ☐ Low

EVALUATION CRITERIA:
Criterion                          Score (1-5)    Notes
────────────────────────────────────────────────────────
Food safety certification           [X]           [cert name/status]
HACCP plan in place                  [X]           [details]
Allergen control program             [X]           [details]
Recall/traceability program          [X]           [details]
Pest control program                 [X]           [details]
Regulatory compliance history        [X]           [any FDA warning letters?]
COA provided with shipments          [X]           [details]

OVERALL SCORE: [X]/35

DECISION:
☐ Approved  ☐ Conditionally Approved  ☐ Not Approved
Conditions: [if conditional]

Review Date: [next annual review]
Approved By: ______________ Date: __________
```
