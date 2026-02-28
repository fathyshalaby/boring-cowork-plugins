# Command: /hvac:load-calc

Perform a preliminary heating/cooling load estimate for equipment sizing.

## Required Information
- Square footage of conditioned space
- Climate zone or city/state
- Insulation quality (poor / average / good / excellent)
- Window type and approximate window area
- Number of occupants
- Stories and ceiling height
- Existing equipment size (if replacing)

## Process
1. Gather the inputs listed above.
2. Apply adjustment factors based on insulation, climate, orientation, and window area.
3. Calculate approximate BTU/hour for heating and cooling.
4. Recommend equipment tonnage (1 ton = 12,000 BTU/hour).
5. **Clearly state this is a PRELIMINARY estimate.** A proper Manual J calculation by a certified technician is required before installation.

## Output Format
```
PRELIMINARY LOAD ESTIMATE
Location: [City, ST] | Climate Zone: [X]
Building: [X] sq ft | [X] stories | [X]ft ceilings

Estimated Cooling Load: [X] BTU/hr ([X] tons)
Estimated Heating Load: [X] BTU/hr

Recommended Equipment Size: [X]-ton system

Basis: [summary of factors considered]

⚠️ DISCLAIMER: This is a preliminary estimate only. A full Manual J
calculation is required per ACCA standards before equipment selection.
```
