# Command: /elevator:parts-request

Generate a parts request form for ordering elevator components.

## Output Format
```
PARTS REQUEST
Date: [date] | Requested By: [name]
Unit: [ID] | Location: [building]
Manufacturer: [name] | Model: [model] | Serial: [serial]

PARTS NEEDED:
#  Part Description    Part Number    Qty    Urgency     Est. Cost
────────────────────────────────────────────────────────────────────
1  [description]       [number]       [X]    [Emergency/Standard]  $[X]

REASON FOR REQUEST:
[Why is this part needed? Describe the failure or PM requirement]

UNIT STATUS:
☐ Unit running with deficiency
☐ Unit shut down pending parts

SUGGESTED SUPPLIERS:
[Supplier name, contact, estimated lead time]

APPROVAL: ______________ Date: __________
```
