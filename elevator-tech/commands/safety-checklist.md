# Command: /elevator:safety-checklist

Generate a safety test checklist for Category 1, 3, or 5 testing.

## Output Format
```
SAFETY TEST CHECKLIST
Unit: [ID] | Type: [Traction/Hydraulic] | Category: [1/3/5]
Date: [date] | Technician: [name] | Inspector: [name]

TEST ITEMS:
#  Test                    Requirement         Result    Pass?
─────────────────────────────────────────────────────────────
1  Door interlock test      Each floor          [result]  ☐
2  Safety circuit check     All devices         [result]  ☐
3  Emergency stop           Car top & pit       [result]  ☐
4  Fire service Phase I     Auto recall         [result]  ☐
5  Fire service Phase II    Manual control      [result]  ☐
[etc. per category]

DEFICIENCIES FOUND:
[List with code reference and required corrective action]

NEXT TEST DUE: [date]
Signatures: Tech _______ Inspector _______
```
