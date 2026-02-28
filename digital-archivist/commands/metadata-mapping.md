# Command: /archive:metadata-mapping

Generate a metadata crosswalk mapping between two standards.

## Output Format
```
METADATA CROSSWALK
Source: [standard A] → Target: [standard B]

Source Field      Target Field       Transformation
────────────────────────────────────────────────────
[field]           [field]            [direct map / rule]
[field]           [field]            [transformation note]

UNMAPPED FIELDS (Source): [list]
UNMAPPED FIELDS (Target): [list]
NOTES: [special considerations]
```
