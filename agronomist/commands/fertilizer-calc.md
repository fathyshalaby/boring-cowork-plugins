# Command: /agronomist:fertilizer-calc

Generate a field-specific fertilizer recommendation based on soil test results and crop yield goals.

## Required Input
- Crop and target yield
- Soil test results (pH, P, K, OM, CEC)
- Previous crop and any N credits
- Field size (acres)

## Output Format
```
FERTILIZER RECOMMENDATION
Field: [name] | Acres: [X]
Crop: [crop] | Yield Target: [X bu/acre or tons/acre]
Previous Crop: [crop] | N Credit: [X lbs/acre]

SOIL TEST SUMMARY:
pH: [X] | P: [X] ppm | K: [X] ppm | OM: [X]% | CEC: [X]

NUTRIENT RECOMMENDATIONS (lbs/acre):
Nutrient     Crop Need    Soil Credits    Recommended    Source
──────────────────────────────────────────────────────────────
Nitrogen     [X]          [X]             [X]            [UAN/Anhydrous/Urea]
Phosphorus   [X]          [X]             [X]            [DAP/MAP/11-52-0]
Potassium    [X]          [X]             [X]            [Potash/0-0-60]
Sulfur       [X]          [X]             [X]            [AMS/Gypsum]
[Lime if pH adjustment needed]

APPLICATION TIMING:
[Recommended timing for each nutrient application]

TOTAL PRODUCT PER FIELD:
[Product] × [rate/acre] × [acres] = [total tons or gallons]

ESTIMATED COST: $[X]/acre | $[X] total
```
