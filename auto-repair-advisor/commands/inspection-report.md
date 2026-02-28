# Command: /auto:inspection-report

Generate a color-coded multi-point inspection report for a customer.

## Output Format
```
MULTI-POINT VEHICLE INSPECTION REPORT
Vehicle: [Year Make Model] | Mileage: [X]
Customer: [name] | Date: [date]

COMPONENT           MEASUREMENT    STATUS    NOTES
────────────────────────────────────────────────────────
BRAKES:
  Front Pads         [X]mm          🟢🟡🔴    [note]
  Rear Pads          [X]mm          🟢🟡🔴    [note]
  Brake Fluid        [color]        🟢🟡🔴    [note]

TIRES:
  LF                 [X]/32"        🟢🟡🔴    [pressure: X PSI]
  RF                 [X]/32"        🟢🟡🔴    [pressure: X PSI]
  LR                 [X]/32"        🟢🟡🔴    [pressure: X PSI]
  RR                 [X]/32"        🟢🟡🔴    [pressure: X PSI]

UNDER HOOD:
  Engine Oil         [level/cond]   🟢🟡🔴    [note]
  Coolant            [level/cond]   🟢🟡🔴    [note]
  Battery            [voltage]      🟢🟡🔴    [load test result]
  [etc.]

🟢 = Good condition
🟡 = Attention needed soon
🔴 = Immediate attention required

RECOMMENDATIONS:
1. [Repair/service recommended with estimated cost]
```
