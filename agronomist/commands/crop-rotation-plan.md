# Command: /agronomist:crop-rotation-plan

Generate a multi-year crop rotation plan for a farm operation.

## Output Format
```
CROP ROTATION PLAN
Farm: [name] | Total Acres: [X]
Planning Period: [Year 1] through [Year X]

FIELD-BY-FIELD ROTATION:
Field    Acres   Year 1    Year 2    Year 3    Year 4    Cover Crop
──────────────────────────────────────────────────────────────────────
[name]   [X]     Corn      Soybeans  Wheat     Corn      Cereal Rye
[name]   [X]     Soybeans  Corn      Corn      Soybeans  Radish
[etc.]

ROTATION RATIONALE:
[Explanation of pest break, N credit, soil health, and market considerations]

NITROGEN CREDITS BY FIELD:
[N credits from previous legume crops to reduce fertilizer costs]

ESTIMATED INPUT COST IMPACT:
[How the rotation affects overall input costs vs. continuous cropping]
```
