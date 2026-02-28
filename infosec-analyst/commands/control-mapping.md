# Command: /infosec:control-mapping

Generate a control mapping between frameworks.

## Output Format
```
SECURITY CONTROL MAPPING
Primary Framework: [e.g., NIST CSF]
Mapped To: [e.g., ISO 27001, CIS Controls, SOC 2]

Control ID    NIST CSF           ISO 27001    CIS Control    SOC 2 TSC
──────────────────────────────────────────────────────────────────────────
[ID]          [control]          [A.X.X]      [IG X.X]       [CC X.X]

GAP ANALYSIS:
Framework    Total Controls    Mapped    Gaps
──────────────────────────────────────────────
[framework]  [X]               [X]       [X]

GAP DETAILS:
[Controls without mapping and recommended actions]
```
