# Command: /ce:risk-entry

Generate a completed risk assessment row mapped to EN ISO 12100 logic.

## Output Format
```
RISK ASSESSMENT: [Hazard/Component Name]
Lifecycle Phase: [Operation / Maintenance / Installation]

1. HAZARD IDENTIFICATION
- Description: [E.g., Crushing hazard between moving carriage and fixed frame].
- Foreseeable Event: [Operator reaches into the machine while carriage is cycling to clear a jam].

2. INITIAL RISK SCORING (Before Mitigation)
- Severity (S1/S2): [E.g., S2 - Severe/irreversible injury]
- Probability (O1/O2/O3): [E.g., O2 - Medium likelihood]
- Avoidance (A1/A2): [E.g., A2 - Not possible to avoid]
- Initial Risk Index: HIGH

3. RISK REDUCTION MEASURES (Follow Hierarchy!)
- Step 1 (Inherently Safe Design): [Can distance be increased? Can force be limited to <150N?]
- Step 2 (Safeguarding): [Install fixed perimeter guard and safety interlock gate rated Performance Level (PL) 'd'. Clause reference: EN ISO 14120]
- Step 3 (Information for Use): [Placard ISO 7010-W024 crushing warning sign. Detail LOTO in manual].

4. FINAL RESIDUAL RISK SCORING
- Severity: [S2]
- Probability: [O1 - Rare]
- Avoidance: [A1 - Possible under specific conditions]
- Residual Risk Index: LOW (Acceptable)
```
