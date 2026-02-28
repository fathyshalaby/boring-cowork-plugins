# Command: /fleet:dot-compliance-check

Generate a DOT/FMCSA compliance checklist for a commercial vehicle.

## Output Format
```
DOT COMPLIANCE CHECKLIST
Unit: [ID] | GVWR: [X] lbs | DOT#: [X]
Date: [date] | Reviewed By: [name]

VEHICLE COMPLIANCE:
☐ Annual inspection current (expires: [date])
☐ DVIR completed daily
☐ Fire extinguisher (charged, mounted)
☐ Triangles/warning devices
☐ Vehicle markings (DOT#, company name)

DRIVER COMPLIANCE:
☐ Valid CDL (class: [X], expires: [date])
☐ DOT medical certificate (expires: [date])
☐ MVR on file (dated: [date])
☐ HOS compliance (ELD recorded)
☐ Drug/alcohol testing current

DEFICIENCIES: [list any]
CORRECTIVE ACTION DUE: [date]
```
