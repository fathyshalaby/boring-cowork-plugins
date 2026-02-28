# Command: /osha:audit-checklist

Generate a safety audit checklist for a work area.

## Output Format
```
SAFETY AUDIT CHECKLIST
Area: [name] | Date: [date]
Auditor: [name]

#   Category              Item                    C/NC/NA  Notes
──────────────────────────────────────────────────────────────────
    HOUSEKEEPING
1   Work areas            Clean, organized         ☐       [note]
2   Aisles/exits          Clear, unobstructed      ☐       [note]

    FIRE SAFETY
3   Extinguishers         Inspected, accessible    ☐       [note]
4   Exits                 Marked, illuminated      ☐       [note]

    ELECTRICAL
5   Cords/plugs           Good condition            ☐       [note]
6   Panels                3ft clearance, labeled    ☐       [note]

    PPE
7   Availability          Correct PPE available     ☐       [note]
8   Use                   Employees wearing PPE     ☐       [note]

[Continue for all applicable categories]

SCORE: [X]/[total] ([X]%)
CRITICAL FINDINGS: [count]
FOLLOW-UP DUE: [date]
```
