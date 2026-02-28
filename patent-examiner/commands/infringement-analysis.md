# Command: /patent:infringement-analysis

Generate a patent infringement analysis worksheet.

## Output Format
```
INFRINGEMENT ANALYSIS
Patent: US [number] | Issue Date: [date]
Accused Product/Process: [description]

CLAIM [X] ELEMENT-BY-ELEMENT COMPARISON:
Claim Element          Accused Product Feature    Match?
──────────────────────────────────────────────────────────
"[claim language]"     [corresponding feature]    ☐ Literal / ☐ DOE / ☐ No

ANALYSIS:
Literal Infringement: ☐ Yes ☐ No
Doctrine of Equivalents: ☐ Yes ☐ No

VALIDITY CONSIDERATIONS:
[Any prior art or §101/112 concerns]

DESIGN-AROUND OPTIONS:
[Potential modifications to avoid infringement]

RISK ASSESSMENT: [Low/Medium/High]
```
