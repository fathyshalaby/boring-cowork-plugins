# Command: /food:haccp-log

Generate a HACCP CCP monitoring log template.

## Output Format
```
HACCP CCP MONITORING LOG
Facility: [name] | Date: [date]
CCP: [#/name] | Critical Limit: [limit]

Time    Product/Lot    Reading    Within Limit?    Initials    Corrective Action
──────────────────────────────────────────────────────────────────────────────────
[time]  [product]      [temp/ph]  ☐ Yes ☐ No       [init]      [if No: action]

Calibration Check: ☐ Completed (result: [X])
Reviewed By: ______________ Date: __________
```
