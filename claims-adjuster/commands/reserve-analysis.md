# Command: /claims:reserve-analysis

Generate a structured reserve analysis for a pending claim.

## Output Format
```
RESERVE ANALYSIS WORKSHEET
Claim #: [number] | Date of Loss: [date]
Claimant: [name] | Type: [Auto/Property/Liability/WC]
Adjuster: [name] | Date of Analysis: [date]

CURRENT RESERVES:
Coverage            Current Reserve    Payments to Date    Remaining
──────────────────────────────────────────────────────────────────────
Indemnity (BI/PD)   $[X]              $[X]                $[X]
Medical             $[X]              $[X]                $[X]
Expense (LAE)       $[X]              $[X]                $[X]
TOTAL               $[X]              $[X]                $[X]

EVALUATION FACTORS:
Liability Assessment: [% at fault, clear/disputed]
Injury Severity: [description]
Medical Treatment Status: [ongoing/MMI/completed]
Attorney Represented: [Yes/No]
Litigation Status: [Pre-lit/Suit filed/Discovery/Trial date]

RESERVE ADEQUACY ANALYSIS:
[Detailed justification for current reserve or recommendation
for increase/decrease with supporting rationale]

RECOMMENDATION:
☐ Reserve adequate—no change
☐ Increase reserve to $[X] — Reason: [justification]
☐ Decrease reserve to $[X] — Reason: [justification]

Approved by: ______________ Date: ______________
```
