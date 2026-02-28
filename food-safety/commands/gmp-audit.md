# Command: /food:gmp-audit

Generate a GMP audit checklist for a food facility.

## Output Format
```
GMP AUDIT CHECKLIST
Facility: [name] | Date: [date]
Auditor: [name]

#   Category              Item                            C/NC    Notes
──────────────────────────────────────────────────────────────────────────
    PERSONNEL HYGIENE
1   Handwashing           Proper technique observed        ☐      [note]
2   Dress code            Hair restraints, clean uniform   ☐      [note]
3   Illness policy        Policy posted, understood        ☐      [note]

    FACILITY
4   Floors                Clean, good repair               ☐      [note]
5   Walls/Ceilings        No damage, peeling               ☐      [note]
6   Lighting              Adequate, shields in place        ☐      [note]

[Continue for all GMP categories]

SCORE: [X] / [total] ([X]%)
CRITICAL NON-CONFORMANCES: [count]
CORRECTIVE ACTIONS DUE: [date]
```
