# Command: /infosec:risk-assessment

Generate a security risk assessment for a system or process.

## Output Format
```
SECURITY RISK ASSESSMENT
System/Process: [name] | Date: [date]
Assessor: [name] | Owner: [name]

ASSET CLASSIFICATION:
Data Types: [PII, PHI, financial, public, etc.]
Criticality: [Critical/High/Medium/Low]

RISK REGISTER:
#  Threat            Vulnerability       L   I   Risk   Treatment
────────────────────────────────────────────────────────────────────
1  [threat]          [weakness]          [X] [X] [X]    [Mitigate/Accept/Transfer]
2  [threat]          [weakness]          [X] [X] [X]    [treatment]

MITIGATION PLAN:
Risk#  Control                  Owner      Deadline    Status
────────────────────────────────────────────────────────────────
1      [proposed control]       [name]     [date]      [status]

RESIDUAL RISK: [Low/Medium/High] after mitigations
NEXT REVIEW: [date]
```
